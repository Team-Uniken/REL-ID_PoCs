Table of Contents
1.	Introduction	4
1.1.	Prerequisite	4
2.	Installation Procedure	4
2.1.	Download and Installation of REL-ID client on the machine	4
2.2.	Launch REL-ID SecureApp	4
2.3.	Set Connection Profile	5
2.4.	Get User ID and Activation Credentials	5
3.	One Time Activation	5
4.	Subsequent Login	9



#Document Control Information

####Basic Details

| **Document File Name** | REL-ID User Manual 		              |
|------------------------|----------------------------------------|
| **Version \#**         | 1.0                                    |
| **Release Date**       | 02-Mar-2016                            |
| **Author**             | Anant Chitale                          |
| **Document Owner**     | Chetan Bokariya                        |
   
####Modification Summary

| **Version** | **Created / Modified By** | **Modification Date** | **Modification Notes** |
|-------------|---------------------------|-----------------------|------------------------|
| 0.1         | Anant Chitale             | 02-Mar-2016           | Initial draft          |
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




#1.	Introduction 
The purpose of this document is to outline process and detailed steps involved in the REL-ID Secure Access (REL-ID APP) Installation and Activation. 

##1.1	Prerequisite 
* User would be shared Activation Credentials (Verification Key & Activation Code) by Uniken Administrator for Activating User ID 
* User Machine should have access to Internet


#2.	Installation Procedure 
##2.1	Download and Installation of REL-ID client on the machine
* User can download REL-ID client from the following link: http://46.137.245.22:8080/REL-ID\_Client/REL-ID\_SecureApp\_windows4.3.0.19.msi 
OR
Download it from the URL shared by the administrator and Save the MSI on the Local machine.
* Double Click on the “REL-ID_SecureApp.msi” to install. 
* On successful installation a shortcut to REL-ID SecureApp will be created on the Desktop. 

##2.2 Launch REL-ID SecureApp
* Double click on the “REL-ID SecureApp” shortcut placed on Desktop or Locate and Run the EXE in the REL-ID Folder to Launch the REL-ID application.  

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture1.png"/>

* The following REL-ID App will be launched

##2.3	Set Connection Profile
* This step is not required in a production (Go Live) scenario as the connection profile will be hard coded/burnt into the REL-ID SecureApp. 
* Along with the user activation credentials, the user would receive a text file to set the connection configuration. 
* Save the configuration file at the location where you installed the REL-ID SecureApp client.
* Launch REL-ID client and click on “Settings”  icon on the right hand top corner of the widget. 
* In the window that appears select the “Connection Profile” tab and click on the Add button (the cross in the top right).

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture2.png"/>

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture3.png"/>

* Click on **Browse** and select the profile created for you by the Uniken PoC team, usually in a “**.txt**” file.
* Click on “**Import Profile**”
* You will see the name of the profile created for you by the Uniken PoC team.  Check with the team if you do not seet it.
* Select that profile and click **Save**.

##2.4.	Get User ID and Activation Credentials 
* User will receive the User Activation credentials (Verification Key and Activation Code) from Uniken Administrator. 

#3.	One Time Activation
* Launch REL-ID SecureApp client. 
* Click on Log-in. 
* The app then performs a set of functions that will:
	* Secure the device
	* Compute a device fingerprint 
	* Establish a simultaneously, mutually authenticated channel (Primary Channel) between the REL-ID SecureApp client and the REL-ID Gateway Server.


<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture4.png"/>

* In the User Verification window - Enter the User-ID that is received from Uniken Administrator and Click on Submit

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture5.png"/>

* As you are a first time User - The New User Activation window will appear. Match the Verification key displayed in the window with the verification key received from Uniken Administrator. Enter the corresponding Activation code in the Activation code field and click on Submit

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture6.png"/>


* If the credentials are authenticated following screen will open where User has to set his secret question and answer for activating the REL-ID on another machine 
* Set Secret Question (Either select one of the existing questions or User can set his own secret question) and Answer – representation screens below 


<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture7.png"/>

* After setting the Secret Question and Answer, user will be asked to set the REL-ID PIN 

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture8.png"/>

* Once the REL-ID PIN is set – the Activation is complete and application is ready to use 

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture9.png"/>

* The REL-ID App will have TILES for – RDP access, WebSite Access along with the other settings tiles. 

#4.	Subsequent Login
* Double click on the “REL-ID SecureApp” shortcut placed on Desktop or Locate and Launch the REL-ID application.
* The following REL-ID App will be launched
* Enter the User-ID and Click on Submit
* Please enter the REL-ID PIN which you have set at the time of activation for your User ID.
* Click Submit 

<img src="https://github.com/Team-Uniken/REL-ID_PoCs/blob/master/user-assets/Picture10.png"/>
