+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 72fca158c8bf42248c43f0569948c46a |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Leiyan M. Doga-ong         | DATE PERFORMED:        |          |
|                                  | 09/11/24               |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 09/11/24               |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Managing Services in Linux

# Requirement: 

-   A virtual machine running Linux

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image2.png){width="4.135416666666667in"
height="1.8020833333333333in"}

Complete this lab as follows:

1.  Use the service ---status-all command to list all active and
    inactive services.

List down active and inactive services in the table below. Provide five
(5) services for each column.

  -----------------------------------------------------------------------
  **Active**                             **Inactive**
  -------------------------------------- --------------------------------
  alsa-utils                             anacron

  apport                                 apparmor

  cron                                   bluetooth

  cups                                   console-setup.sh

  dbus                                   cryptdisks
  -----------------------------------------------------------------------

SS:

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image3.png){width="4.238759842519685in"
height="3.84375in"}

2.  Start the Bluetooth service using the systemctl command.

Ex. sudo systemctl start httpd

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image4.png){width="4.359946412948381in"
height="1.1875in"}

3.  Check the status of the Bluetooth service. What is its status?

-   The status of the Bluetooth is inactive.

SS:

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image5.png){width="7.027083333333334in"
height="0.9020833333333333in"}

1.  Check the status of the cups services. Since when was it running?

-   The status of the cups services is running since Wed 2024-09-11.

SS:

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image6.png){width="7.027083333333334in"
height="3.2618055555555556in"}

1.  Stop cups services.

> SS:
>
> ![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image7.png){width="7.027083333333334in"
> height="3.395138888888889in"}

2.  Verify if the service was stopped.

SS:

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image8.png){width="7.027083333333334in"
height="0.8666666666666667in"}

3.  Restart the cups services

SS:

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image9.png){width="5.521604330708661in"
height="0.4271434820647419in"}

4.  Verify if the service was restarted.

SS:

![](vertopal_72fca158c8bf42248c43f0569948c46a/media/image10.png){width="7.027083333333334in"
height="3.2881944444444446in"}
