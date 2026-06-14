# APP: SCAN_VAULT
 - link: <https://bcs-vault.vercel.app>

## QUICK START
- Once app is installed: the very first time you hit (START) in the app, the app will request permission to use the camera
- App by default is set to *Local Mode* thus you should be able to get images and save them into your device. At end of  each scan, the app will ask you where to store them. 
- ***Alternatively:*** A tech savvy friend can help you with setting up the app to save images remotely. To store images remotely to Google Drive, Section 3 (Acount Configuration) in the settings will need to be filled out.

- **Tip**:
  - place the account credentials in a csv file and upload them into the app.. See next section.
  - Switch Storage Mode from Local to Remote in other to view the Private / Team account configuration section
  
## CREDENTIALS: UPLOADING CSV
==========================
> for more details on authentication, csv and app usage, please see the "guide" found in the app's settings)

Note  you may have upto two accounts' credentials saved on the app (Private, Team), but only one active at a time.  

-  If user is authenticating using OAuth. *Info required*:  

        -  google oauth client id, google folder id, google sheet id, sheet tab name  

-  If user is authenticating using Service Account. *Info required*:  

        -  drive client email, drive private key, google folder id, google sheet id, sheet tab name

Instead of entering the credentials manually in the Private/Team Config Section u may place 1 or both credential in a csv file. (Comma separated) 

##  Example  

Below represents the content of a csv file where user is authenticating using OAuth: 

| <sub>ACCOUNT</sub> | <sub>GOOGLE_OAUTH_CLIENT_ID</sub> | <sub>DRIVE_CLIENT_EMAIL</sub> | <sub>DRIVE_PRIVATE_KEY</sub> | <sub>GOOGLE_DRIVE_FOLDER_ID</sub> | <sub>GOOGLE_SHEET_ID</sub> | <sub>SHEET_NAME</sub> | <sub>Is_Current</sub> |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| <sub>private</sub> | <sub>xxx.apps.googleus.com</sub> | <sub></sub> | <sub></sub> | <sub>4_ioerjSFFDFGDFGFddL2</sub> | <sub>6B-kdkdliDd334a</sub> | <sub>Sheet1</sub> | <sub>1</sub> |
| <sub>team</sub> | <sub></sub> | <sub></sub> | <sub></sub> | <sub></sub> | <sub></sub> | <sub></sub> | <sub>0</sub> |
         

