# APP: SCAN_VAULT
 - link: <https://bcs-vault.vercel.app>

## QUICK START
- Once app is installed: the very first time you hit (START) in the app, the app will request permission to use the camera
- App by default is set to *Local Mode* thus images will be directed to be save locally. At the end of  each scan, the app will ask you where to store/share them. 
- ***Alternatively:*** A tech savvy friend can help you with setting up the app to save images remotely. To store images to Google Drive, Section 3 (Acount Configuration) in the settings will need to be filled out.

- **Tip**:
  - place the account credentials in a csv file and upload them into the app.. See next section.
  - Switch Storage Mode from Local to Remote in order to view the Private / Team account configuration section
  
## CREDENTIALS: UPLOADING CSV
==========================
> for more details on authentication, csv and app usage, please see the "guide" found in the app's settings)

Note  you may have upto two accounts' credentials saved on the app (Private, Team), but only one active at a time.  

-  If user is authenticating using OAuth. *Info required*:  

        -  google_oauth_client_id, google_drive_folder_id, google_sheet_id, sheet_name  

-  If user is authenticating using Service Account. *Info required*:  

        -  drive_client_email, drive_private_key, google_drive_folder_id, google_sheet_id, sheet_name 

Instead of entering the credentials manually in the Private/Team Config Section u may place 1 or both credential in a csv file. (Comma separated) 

##  Example  

Below represents the content of a csv file where user is authenticating using OAuth: 

| <sub>account</sub> | <sub>google_oauth_client_id</sub> | <sub>drive_client_email</sub> | <sub>drive_private_key</sub> | <sub>google_drive_folder_id</sub> | <sub>google_sheet_id</sub> | <sub>sheet_name</sub> | <sub>is_current</sub> | <sub>web_origin</sub> |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| <sub>private</sub> | <sub>xxx.apps.googleus.com</sub> | <sub></sub> | <sub></sub> | <sub>4_ioerjSFFDFGDFGFddL2</sub> | <sub>6B-kdkDd334a</sub> | <sub>Sheet1</sub> | <sub>1</sub> |<sub>https://bcs-vault.vercel.app/callback</sub> |
| <sub>team</sub> | <sub></sub> | <sub></sub> | <sub></sub> | <sub></sub> | <sub></sub> | <sub>Sheet1</sub> | <sub>0</sub> | <sub>https://bcs-vault.vercel.app/callback</sub> |
         

