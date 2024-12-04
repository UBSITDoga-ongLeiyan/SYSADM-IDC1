+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| 1f49f1c53e0b48d7835dd9688a3f671f |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Leiyan M. Doga-ong         | DATE PERFORMED:        | /50      |
|                                  | 10/16/2024             |          |
+----------------------------------+------------------------+----------+
| Section: IDC1                    | DATE SUBMITTED:        |          |
|                                  | 10/16/2024             |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Setting Up Webserver

# Requirement: 

-   A virtual machine running Linux and Windows OS

    Task Instructions:

1.  Install IIS by adding it as a role, select necessary features,
    include monitoring tools

    ![](vertopal_1f49f1c53e0b48d7835dd9688a3f671f/media/image2.png){width="4.870904418197726in"
    height="4.109538495188102in"}

    ![](vertopal_1f49f1c53e0b48d7835dd9688a3f671f/media/image3.png){width="5.662736220472441in"
    height="2.8271708223972003in"}

2.  Create a website by opening IIS Manager

    -   Right-click on the server's name and select Internet Information
        Services Manager.

    -   Right-click on Sites and select Add Website.

    -   Enter a name, description, physical path (where your website
        files will reside), IP address, port, and host name.

        ![](vertopal_1f49f1c53e0b48d7835dd9688a3f671f/media/image4.png){width="5.5424398512685915in"
        height="1.718989501312336in"}

3.  Configure the Website:

    -   Right-click on your website and select Edit.

    -   Set the Default Document to the name of your main HTML file
        \>default.html

        ![](vertopal_1f49f1c53e0b48d7835dd9688a3f671f/media/image5.png){width="4.928391294838145in"
        height="2.2802996500437445in"}

    -   Configure other settings as needed (e.g., SSL certificates,
        authentication)

4.  Create a Web Page:

    -   Create an HTML file in the physical path you specified.

        ![](vertopal_1f49f1c53e0b48d7835dd9688a3f671f/media/image6.png){width="3.652083333333333in"
        height="1.52377624671916in"}

    -   Save it as default.html or your preferred name.

        ![](vertopal_1f49f1c53e0b48d7835dd9688a3f671f/media/image7.png){width="5.9996784776902885in"
        height="2.019226815398075in"}

5.  Test the Web Server:

    -   Open a web browser and enter the URL of your website (e.g.,
        http://localhost).

    -   You should see your web page displayed.

        ![](vertopal_1f49f1c53e0b48d7835dd9688a3f671f/media/image8.png){width="7.027083333333334in"
        height="3.2666666666666666in"}

Grading Rubric

  ------------------------------------------------------------------------------
  **Criteria**      **Points**   **Description**
  ----------------- ------------ -----------------------------------------------
  Web Server        15           Correctly installs IIS or another web server on
  Installation                   the virtual machine.

  Website           15           Successfully configures the website with the
  Configuration                  correct physical path, IP address, port, and
                                 default document.

  Successful Access 15           Successfully accesses the web page from the
                                 client computer using the correct URL.

  Troubleshooting   15           Demonstrates ability to troubleshoot common
                                 issues, such as network connectivity problems
                                 or configuration errors.

  Documentation     10           Provides clear and concise documentation of the
                                 installation, configuration, and testing
                                 process.

  Total             /70          
  ------------------------------------------------------------------------------
