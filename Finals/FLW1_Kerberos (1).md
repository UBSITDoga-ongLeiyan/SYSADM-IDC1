+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 6640579535934f4db5ba465033a12a7a |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Leiyan M. Doga-ong         | DATE PERFORMED:        | /50      |
|                                  | 11/13/24               |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 11/13/24               |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Kerberos Lab Activity: A step-by-step Guide

**Objective:**

Set up a basic Kerberos authentication system to understand how Kerberos
manages secure logins through ticket-based access.

**Setup Requirements:**

-   Two VMs in Oracle VM, both running a Linux distribution like Ubuntu
    or CentOS.

-   VM1: Kerberos Server

-   VM2: Kerberos Client

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image2.png){width="7.027083333333334in"
height="1.6194444444444445in"}

**Step 1: Initial Setup and Package Installation**

1.  **Update Packages on Both VMs:**

    -   Open a terminal on each VM and run:

*bash*

*sudo apt update && sudo apt upgrade --y*

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image3.png){width="7.027083333333334in"
height="2.7583333333333333in"}
![](vertopal_6640579535934f4db5ba465033a12a7a/media/image4.png){width="7.027083333333334in"
height="2.8645833333333335in"}

2.  **Install Kerberos Server Packages on VM1 (Kerberos Server):**

    -   In VM1, install the Kerberos Key Distribution Center (KDC) and
        admin server:

*bash*

*sudo apt install krb5-kdc krb5-admin-server --y*

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image5.png){width="5.516683070866142in"
height="4.78832239720035in"}
![](vertopal_6640579535934f4db5ba465033a12a7a/media/image6.png){width="5.520477909011373in"
height="4.207325021872266in"}

3.  **Install Kerberos Client Package on VM2 (Kerberos Client):**

    -   In VM2, install the Kerberos client software:

*bash*

*sudo apt install krb5-user -y*

-   During installation, when prompted, enter the Kerberos realm you
    plan to set up, e.g., MYLAB.LOCAL.

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image7.png){width="6.740523840769904in"
height="1.6877351268591425in"}

**Step 2: Configure the Kerberos Server (VM1)**

1.  **Edit the Kerberos Configuration File:**

    -   Open /etc/krb5.conf for editing:

*bash*

*sudo nano /etc/krb5.conf*

-   Set the realm as MYLAB.LOCAL. You should also specify the KDC and
    admin server as VM1's hostname or IP address:

ini

\[libdefaults\]

default_realm = MYLAB.LOCAL

\[realms\]

MYLAB.LOCAL = {

kdc = \<VM1_IP_or_hostname\>

admin_server = \<VM1_IP_or_hostname\>

}

-   Save and close the file (Ctrl+X, then Y, and Enter to confirm).

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image8.png){width="5.323659230096238in"
height="2.1252963692038493in"}

2.  **Initialize the Kerberos Database:**

    -   Create the database for the Kerberos realm:

*bash*

*sudo krb5_newrealm*

-   You will be prompted to set a password for the Kerberos database.

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image9.png){width="4.2714293525809275in"
height="0.739686132983377in"}

3.  **Start and Enable the Kerberos Services:**

    -   Start the KDC and admin server, and ensure they start
        automatically on boot:

*bash*

*sudo systemctl start krb5-kdc*

*sudo systemctl start krb5-admin-server*

*sudo systemctl enable krb5-kdc*

*sudo systemctl enable krb5-admin-server*

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image10.png){width="5.814733158355206in"
height="2.6772244094488187in"}

**Step 3: Set Up a Kerberos User Principal**

1.  **Create a New User Principal:**

    -   Run the following command to create a test user in the Kerberos
        realm:

*bash*

*sudo kadmin.local -q \"addprinc testuser@MYLAB.LOCAL\"*

-   Set a password for testuser.

2.  **Verify the User Principal:**

    -   To confirm the principal is created, list all principals:

*bash*

*sudo kadmin.local -q \"listprincs\"*

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image11.png){width="7.027083333333334in"
height="1.7493055555555554in"}

**Step 4: Configure the Kerberos Client (VM2)**

1.  **Edit the Kerberos Configuration File on VM2:**

    -   Open /etc/krb5.conf for editing on VM2:

*bash*

*sudo nano /etc/krb5.conf*

-   Set the default realm to MYLAB.LOCAL and point to the KDC and admin
    server on VM1. The configuration should match what you set on VM1.

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image12.png){width="5.511185476815398in"
height="2.1461329833770777in"}

**Step 5: Test Kerberos Authentication**

1.  **Request a Kerberos Ticket for the User on VM2:**

    -   In the terminal on VM2, request a ticket for testuser:

*bash*

*kinit testuser@MYLAB.LOCAL*

-   Enter the password you set for testuser.

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image13.png){width="7.027083333333334in"
height="1.1465277777777778in"}

2.  **Verify the Ticket:**

    -   Check if the ticket was issued by listing active Kerberos
        tickets:

*bash*

*list*

-   You should see details about the ticket, such as the principal and
    expiration time, confirming successful Kerberos authentication.

![](vertopal_6640579535934f4db5ba465033a12a7a/media/image14.png){width="6.396725721784777in"
height="1.0418121172353456in"}
