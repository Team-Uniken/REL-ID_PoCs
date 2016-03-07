

#GATEWAY MANUAL

- 1      [INTRODUCTION](#1)
- 2      [LOG-IN](#2)
- 3      [USER](#3)
- 3.1    [User Request](#3.1)
- 3.1.1  [Search](#3.1.1)
- 3.1.2  [Actions](#3.1.2)
- 3.2    [User Management](#3.2)
- 3.2.1  [Search user](#3.2.1)
- 3.2.1.1 [User Details](#3.2.1.1)
- 3.2.1.2 [Administrative Action](#3.2.1.2)
- 3.2.1.3 [Actions](#3.2.1.3)
- 4      [GROUP](#4)
- 4.1    [Group management](#4.1)
- 4.2    [FQDN Management](#4.2)
- 4.2.1  [Search FQDN](#4.2.1)
- 4.3    [Add FQDN](#4.3)
- 4.4    [Actions](#4.4)
- 4.4.1  [Edit FQDN](#4.4.1)
- 4.4.2  [View FQDN Users](#4.4.2)
- 4.4.3  [Synch FQDN Group](#4.4.3)
- 4.4.4  [Synch FQDN Users](#4.4.4)
- 5      [APPLICATION](#4)
- 5.1    [Site Management](#5.1)
- 5.1.1  [Edit Site](#5.1.1)
- 5.1.2  [Add Site](#5.1.2)
- 5.1.3  [Search Site](#5.1.3)
- 5.1.4  [Delete Site](#5.1.4)
- 5.2    [Application Group](#5.2)
- 5.2.1  [Search Application Group](#5.2.1)
- 5.2.2  [Add Application Group](#5.2.2)
- 5.2.3  [Delete Application Group](#5.2.3)
- 5.2.4  [Bulk Action](#5.2.4)
- 5.3    [Application Management](#5.3)
- 5.3.1  [Search](#5.3.1)
- 5.3.2  [Add/View/Edit Application](#5.3.2)
- 5.3.3  [Delete Application](#5.3.3)
- 6      [REPORTS](#6)
- 6.1    [User Reports](#6.1)
- 6.1.1  [Audit report](#6.1.1)
- 6.1.2  [User Statistics Report](#6.1.2)
- 6.2    [Server Report](#6.2)
- 6.2.1  [Server Access Report](#6.2.1)
- 6.2.2  [Server Monitoring Report](#6.2.2)
- 6.2.3  [SMS Pusher Report](#6.2.3)
- 6.2.4  [Email Pusher Report](#6.2.4)
- 6.2.5  [User Detailed Report](#6.2.5)
- 7      [ADMINISTRATION](#7)
- 7.1    [Console User Management](#7.1)
- 7.1.1  [Search](#7.1.1)
- 7.1.2  [Add New Console User](#7.1.2)
- 7.1.3  [Actions](#7.1.3)
- 8      [LICENSE](#8)
- 8.1    [License Management](#8.1)
- 8.1.1  [The Overview Tab](#8.1.1)
- 8.1.2  [Action Tab](#8.1.2)
- 8.1.3  [License Upload](#8.1.3)


###Document Control Information

####Basic Details

| **Document File Name** | REL-ID Gateway\_Manager\_ManualForNWD2 |
|------------------------|----------------------------------------|
| **Version \#**         | 1.0                                    |
| **Release Date**       | 04-Mar-2016                            |
| **Author**             | Anant Chitale                          |
| **Document Owner**     | Chetan Bokariya                        |
   
####Modification Summary

| **Version** | **Created / Modified By** | **Modification Date** | **Modification Notes** |
|-------------|---------------------------|-----------------------|------------------------|
| 0.1         | Anant Chitale             | 04-Mar-2016           | Initial draft          |
| 1.0         | Chetan Bokariya           |                       | Baseline               |


####Contacts for Inquiries and Proposed Changes
If you have any questions or suggestions regarding the contents of this document, please contact:

| **Name**          | Chetan Bokariya               |
|:--------------------|:-------------------------------|
| **Designation**   | AVP Mobile Technical Presales |
| **Phone**         | +91-20-66427970/71/72/73      |
| **E-mail**        | <chetan.bokariya@uniken.com>  |

####Proprietary Notice

This publication has been prepared and published by Uniken Innovation Center and is copyright. No part of this document may in any form or by any means (electronic, mechanical, micro-copying, photocopying, recording or otherwise) be reproduced, stored in a retrieval system or transmitted without prior written permission from the document controller. Product or company names are trademarks of their respective holders.

Due care has been taken to make this document as accurate as possible. However, Uniken makes no representation or warranties with respect to the contents hereof and shall not be responsible for any loss or damage caused to the user by the direct or indirect use of this document. Furthermore, Uniken reserves the right to alter, modify or otherwise change in any manner the content hereof, without obligation of Uniken to notify any person of such revision or changes.

The Document Control Information section contains the contact details for inquiries, comments and to propose changes to the document.

<br>
<br>







<a name="1"></a>
#1 Introduction

REL-ID Gateway Manager (GM) is a web application that provides the administrator a graphical interface to manage REL-ID users and applications. This manual is specifically designed to help a Level 3 (L3) administrator to learn how to carry out the necessary day-to-day operations with REL-ID. Through this portal, the L3 administrator will be able to manage and monitor activities performed by the operators.

The tutorial covers the following modules:

1.  LOG-IN
2.  USER
3.  GROUP
4.  APPLICATION
5.  ADMINISTRATION
6.  REPORTS
7.  LICENSE

<br>
<br>


<a name="2"></a>
#2 LOG-IN

Before you can start this tutorial you must have the login credentials required to log-into the REL-ID GM and the link to GW web application.

You can launch the GM web application in a web browser and log-into REL-ID GM using the credentials.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture1.png"/>

On successful login, you will enter the GM and will be able to see the following menu items:

User | Group | Application | Server management | Report | Administrator | License


<br>
<br>


<a name="3"></a>
#3 USER

This module enables you to monitor, enroll and manage users. This module comprises of the following sub-modules:

<a name="3.1"></a>
##3.1 User Request

Here you can view all the user related activities performed by the other operators.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture2.png" />

<a name="3.1.1"></a>
###3.1.1 Search

Through “Search” you will be able to see all the activities performed by other operators. You can filter your search based on

1.  User ID/Group/Agent and Server ID (In case there are multiple REL-ID Gateway Servers)
2.  Request status – Pending/Processed/Discarded etc.
3.  User Type – User/Group/Agent/Server

You can see activities categorized under - Request ID, ID (User ID), Request Type, Comments (if any), Status of the request, User Type (User, Group, Agent or Server), Creator (Admin user ID), Creation Time Stamp, Return Message (Success/Failure) and attempt counter.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture3.png"/>

<a name="3.1.2"></a>
###3.1.2 Actions

You can select pending request/s and discard only those requests generated by you.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture4.png"/>

<a name="3.2"></a>
##3.2 User Management

Click on user button and select User Management from the drop down menu. You will see the below screen

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture5.png"/>

<a name="3.2.1"></a>
###3.2.1 Search user

You can also search for an existing enrolled user. Enter user ID and click “**Search**”

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture6.png"/>

OR

you can select only the Group Name from the list and click “**Search**”. All users in the group will be listed. Click on the user ID you need and view the user details.

If the search fields are empty and search button is clicked, it will present the list of all the users.

You can perform the following bulk activities by selecting users from the list.

Select users by checking the check box provided in the first column. You can select all or multiple users.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture7.png"/>


**Remove All Parameters**: Enables you to remove user level parameters if set

**Get Selected User Credentials**: You can select users from the list and get user credentials (activation credentials) for the selected users in .csv/.xlsx format.


<a name="3.2.2"></a>
###3.2.2 User Details

Individual user ID search or clicking on User ID from the searched list will display details of the users under following tab:

1.  **Overview**
    -   **User Status** (Created/Active/Suspended/Paused/Terminated)
    -   **User enrollment time stamp**
    -   **User ID**
    -   **Group Name**
        <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture8.png"/>
2.  **User Request**: Provides details on the various administrative activities performed for the user.
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture9.png"/>
3.  **Application Group Details**: This tab displays the list of all the application groups created and provides the administrator an interface to link users to the applications.
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture10.png"/>
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture11.png"/>
4.  **Device Details**: Provides a list of all the devices that are bound to the user along with details of UUID, Device ID, Device Alias (as set by the user), Device Status and provision to Delete All Devices.
    - Delete Device - to delete individual device
    - Delete Device and All Bindings – enables you to delete all the users bound to that device.
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture12.png"/>


<a name="3.2.3"></a>
###3.2.3 Administrative Action

Administrative Action enables you to:

1.  **Regenerate Credentials**: In case an enrolled user has lost or misplaced the user credentials, you can regenerate the user credentials by opting for this option.

    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture13.png"/>


2.  **Get User Credentials:** After successful enrolment of a User, the Activation credentials (Verification Key and Activation Code) will be delivered to the user via configured channel i.e. SMS/Email/Snail Mail. In case you need to access the user credentials it can be made available in an .xlsx/.csv file format.

3.  **View Configuration:** You will be able to view (only) the configurations set (if any) for the user. Configurations including- Button Config, Tunnel Config, Tunnels, User Settings and Device Binding Configurations.

    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture14.png"/>


4.  **General Settings:** Enables you to view and edit the following settings
    a.  **User Settings:** This feature allows you to set the user settings in-respect to
        <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture15.png"/>
                
    *  SSO Settings
    *  Biometric
    *  Expiry Time
    *  Clip Board
    *  Version Info
    *  Tunnel Proxy
    *  Server Settings
    *  Remove Coolies
    *  Browser Setting


    b.  **Device Binding Configurations:** This feature allows you to set the maximum number of permanent and temporary devices allowed for a user

    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture16.png"/>

    c.  **Application Parameters:** You can set the session time out (in seconds), Password history (Number of previous passwords to be maintained), and Password Expiry (in number of days).
        <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture17.png"/>

5.  **Remove All Parameters:**

Click on “**Remove All Application Params**” to remove previously set parameters.
<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture18.png"/>


<br>
<br>

<a name="4"></a>
#4 GROUP
You can perform user group related activities here. Click on the GROUP icon and select type of activity from the dropdown menu.
<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture19.png"/>


<a name="4.1"></a>
##4.1 Group management

As REL-ID is required to fetch users from the Active Directory, this function is disabled.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture20.png"/>


<a name="4.2"></a>
##4.2 FQDN Management

To Create/Enroll/Add AD-FQDN, select FQDM Management

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture21.png"/>

<a name="4.2.1"></a>
###4.2.1 Search FQDN

You can search FQDN groups added to REL-ID by entering the FQDN name in the search field or click on **Search** keeping the search field empty. This will provide a list of all the FQDN groups included in REL-ID.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture22.png"/>


<a name="4.3"></a>
##4.3 Add FQDN

To add a new FQDN, click on the Add FQDN button. In the window that opens, specify the following:

1.  Fully Qualified Domain Name (FQDN) for the AD group to be included.
2.  IP of the AD
3.  Port on with the AD communicates
4.  User ID of the Administrator for the AD group
5.  Password for the User ID
6.  Re-enter the password
7.  In case the AD uses Kerberos authentication enable the authentication by selecting.
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture23.png"/>

Clicking on Save will create an FQDN group. To fetch AD FQDN group users please refer Synch FQDN Users


<a name="4.4"></a>
##4.4 Actions

You can perform the following activities on the FQDN group created. Select an FQDN group from the list and click on Actions.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture24.png"/>


<a name="4.4.1"></a>
###4.4.1 Edit FQDN

You can make changes to the existing FQDN through the edit button

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture25.png"/>

<a name="4.4.2"></a>
###4.4.2 View FQDN Users

You can view all the users under the selected FQDN group

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture26.png"/>

<a name="4.4.3"></a>
###4.4.3 Synch FQDN Group

If an FQDN has groups, the users along with group will be fetched and updated when you select this option.

<a name="4.4.4"></a>
###4.4.4 Synch FQDN Users

This helps to fetch all the users from the FQDN Group and enroll them into REL-ID. Synching also helps update the REL-ID enrolled user list with the AD FQDN Group.


<br>
<br>


<a name="5"></a>
#5. APPLICATION

The applications which need to be accessible through REL-ID need to be configured in the Gateway Manager.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture27.png"/>

To add a new application:


<a name="5.1"></a>
##5.1 Site Management

Select Site Management. Clicking Search will display all the sites previously added.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture28.png"/>


<a name="5.1.1"></a>
###5.1.1 Edit Site

You can click on the Site Name and view the Site details. Here you can edit the site details and update the site.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture29.png"/>


<a name="5.1.2"></a>
###5.1.2 Add Site

To configure application that needs to be secured their entries have to be added as add site. Click on Add Site button and enter the site details

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture30.png"/>

Click on **Save** the site details. Now provide the Tunnel Target and click on Add Save Target.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture31.png"/>


<a name="5.1.3"></a>
###5.1.3 Search Site

You can enter the site name or click on search button to fetch a list of all the sites that have been added.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture32.png"/>


<a name="5.1.4"></a>
###5.1.4 Delete Site

Select a site from the list and click Delete Site to delete the site.


<a name="5.2"></a>
##5.2 Application Group

You can club a set of applications under an Application Group, and manage the application settings.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture33.png"/>


<a name="5.2.1"></a>
###5.2.1 Search Application Group

Enter the application group name and search to get the application group or click on search with the Application Group Name field empty to fetch a list of all the application groups created.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture34.png"/>


<a name="5.2.2"></a>
###5.2.2 Add Application Group

Click on Add Application Group and fill the required fields and click save. An application group will be created.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture35.png"/>


<a name="5.2.3"></a>
###5.2.3 Delete Application Group

Select application group/s and click on Delete Application Group to delete application groups.


<a name="5.2.4"></a>
###5.2.4 Bulk Action

You can select group/s from the list of application groups and assign configured sites to the groups selected.

1.  Select group/s
2.  Click on Bulk Action and select ‘Assign to Application’
3.  From the list of sites select sites to be assigned and Save
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture36.png"/>

<a name="5.3"></a>
##5.3 Application Management

This interface enables you to add new applications, search/view/modify the existing application settings.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture37.png"/>


<a name="5.3.1"></a>
###5.3.1 Search

Enter the application name and search to get the application group or click on search with the Application Name field empty to fetch a list of all the applications created.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture38.png"/>


<a name="5.3.2"></a>
###5.3.2 Add/View/Edit Application

1.  **Application Details:** You can create an application by providing the required fields
    1.  Name - of the application
    2.  Display Order – as this application will be displayed as a tile on the REL-ID AppSecure Client its display order needs to be assigned.
    3.  Button Type – you can select between
        1.  Web – if it is a web application to open in a default web browser
        2.  Local – To fetch application components from local device For E.g. Mobile app.
        3.  App – in case a third party thick client application needs to be launched
    4.  Select Prefetch – Yes/No
    5.  Browser Mode – Popup/Tab
    6.  URL/Info of App –
        1.  URL- If the button type selected is Web or LOCAL, you need to specify the URL.
        2.  Info of App – when button type selected is App. You need to specify the app info in this pipe separated format: - **External Application Name||Path||Argument**. In case of mobile apps please specify the applications name e.g. Email
    7.  Image – You can select an image to be viewed as tile on the REL-ID SecureApp Client
    8.  Viewer Type – For button type Web/Local the viewer type can be specified as
        1.  Launch App Viewer – Launch application in hardened browser
        2.  Launch Quick App – Launch the application within the REL-ID Secure App Client such as Change PIN, Change Secret Q&A, and Generate OTP. Etc.
    9.  Full Size - Yes/Now
    10. Browser Type – Valid only in case of Web Apps, IE View or Web View.
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture39.png"/>
2.  **Site details:** you can view and associate sit/s to the application
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture40.png"/>
3.  **Application Group**: View and associate Application Group/s to the application. Save application.
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture41.png"/>


<a name="5.3.3"></a>
###5.3.3 Delete Application

Select application/s from the list and click on Delete Application
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture42.png"/>

<br>
<br>


<a name="6"></a>
#6 REPORTS

The Gateway Manager enables you to generate various types of reports. The reports are majorly categorized as User Reports and Server Reports


<a name="6.1"></a>
##6.1 User Reports

You can generate user monitoring reports such as:

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture43.png"/>


<a name="6.1.1"></a>
###6.1.1 Audit report

This report provides details of all the activities performed by Gateway Manager Console Users.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture44.png"/>

Specify the date range and select a report type from the dropdown to generate the report. You will be able to view and download the report in a ‘.csv’ format.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture45.png"/>


<a name="6.1.2"></a>
###6.1.2 User Statistics Report

You can choose to export various types of reports:

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture46.png"/>

**User Statistics Report** – Provide data on access logs for a group, for the specified duration

**User Enrollment Report** – Provides data on total number enrollments in the specified duration

**User Status report** - Provides data on total number All/Active/Created/Reset/To be Reset/ Blocked/Paused/Suspended/Terminated users in the specified duration

**User Rename Log Report** - Provides data on total number users who were renamed in the specified duration

**Server Session Report** - Provides data on user activity for the specified duration

**Prompt Statistics Report** – A comprehensive report for the said duration.


<a name="6.2"></a>
##6.2 Server Report

You can generate reports for all the server related activity


<a name="6.2.1"></a>
###6.2.1 Server Access Report

Generate a detailed or summary report for all or any of the events mentioned in the drop down menu. User/IP specific reports could also be generated.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture47.png"/>


<a name="6.2.2"></a>
###6.2.2 Server Monitoring Report

Helps generate server monitoring for a specific IP or Host name. You can generate current/ hourly/daily and user specific statistic report

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture48.png"/>


<a name="6.2.3"></a>
###6.2.3 SMS Pusher Report

Report on the SMS’s being sent by the server to the SMS Gateway, based on their status (All/Queued/Sent/Failed)

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture49.png"/>


<a name="6.2.4"></a>
###6.2.4 Email Pusher Report

Report on the Email’s being sent by the server, based on their status (All/Queued/Sent/Failed)

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture50.png"/>


<a name="6.2.5"></a>
###6.2.5 User Detailed Report

Helps generate detailed report for a specific user

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture51.png"/>

<br>
<br>


<a name="7"></a>
#7 ADMINISTRATION

It provides you with an interface to create role, administrative console users and assign roles to the users.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture52.png"/>


<a name="7.1"></a>
##7.1 Console User Management

You can view, edit and create console users with this interface.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture53.png"/>


<a name="7.1.1"></a>
##7.1.1 Search

Enter the Login ID and/or specify status and/or roll parameters to conduct the search or click on search with the Login ID field empty and any in the Status and Roles fields to fetch a list of all the enrolled console users.

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture54.png"/>


<a name="7.1.1"></a>
###7.1.2 Add New Console User

    1. Click on the Add New Console User
    2. Specify login ID and password (The user will be prompted to change the password on first login)
    3. Assign a Role (Administrator/Operator) and Click **Save**
   
    <img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture55.png"/>


<a name="7.1.3"></a>
###7.1.3 Actions

You can select the user and perform various activities for the selected console user

1.  Update Role
2.  Suspend user
3.  Activate Console User
4.  Terminate User
5.  Reset Password

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture56.png"/>

<br>
<br>

<a name="8"></a>
#8 LICENSE

<a name="8.1"></a>
#8.1 License Management

You can view license details and upload license

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture57.png"/>

<a name="8.1.1"></a>
###8.1.1 The Overview Tab

**Server Device ID**: Displays the Server ID and the Server Device ID. The Sever Device ID is required to generate renewal/upgrade license. The administrator can export the Server Device ID by clicking on “Export Server Device ID” which is downloaded as a text file.

The administrator sends this Server Device ID file to Uniken and Uniken administrator generates the required license.

**License Details**: This table provides details on the license that include – Server ID, Permitted User Enrollments, Permitted Group Enrollments, permitted Concurrency Settings, License Issue Date, License Expiry Date, Creation Timestamp and Actions

**License Log Details:** Provides details on Server ID’s current timestamp

**Current Server Status**: Provides details on user count, group count and current time stamp


<a name="8.1.2"></a>
###8.1.2 Action Tab

**Upload License:** Enables user to upload license

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/gateway-assets/Picture58.png"/>


<a name="8.1.3"></a>
###8.1.3 License Upload

-   Once the user receives the license from Uniken Administrator, he/she can save it at a location on the local drive.
-   The user then clicks on “Choose file” button to navigate to the location where the license file is placed and selects the license file.
-   Click on Upload License.
-   On successful upload, the user receives a license upload success message.
-   The user then clicks on Reload Page
-   The changes reflect in the Overview tab.


For more information, contact <info@uniken.com>                                                                                        
[Website](http://www.uniken.com)
[LinkedIn ](https://in.linkedin.com/company/uniken-inc)
[Twitter](https://twitter.com/Uniken_Inc)                                                                                                                                           
 © 2016 Uniken Inc. All rights reserved.                                                                                                 
                                                                                                                                         
 **Corporate Office:** 466 Southern Blvd 2nd Flr, Chatham New Jersey 07928 USA | +1 844 33RELID                                          
                                                                                                                                         
 **Innovation Center:** A-901, 9<sup>th</sup> Floor, Sr. No. 103, Teerth Technospace, Baner, Pune 411045 India | +91 20 6725 3900


