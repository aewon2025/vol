 UPLOADING CSV CREDENTIALS
==========================


Note  you may have upto two accounts' credentials saved on the app (Private, Team), but only one active at a time.  

-  If user is authenticating using OAuth. *Info required*:  

        -  google oauth client id, google folder id, google sheet id, sheet tab name  

-  If user is authenticating using service account. *Info required*:  

        -  drive client email, drive private key, google folder id, google sheet id, sheet tab name

Instead of entering the credentials manually in the Private/Team Config Zone u may place 1 or both credential in a csv file.  

The example below represents the content of a csv file where user is authenticating using OAuth:

Account	|GOOGLE_OAUTH_CLIENT_ID	        |DRIVE_CLIENT_EMAIL	|DRIVE_PRIVATE_KEY	|GOOGLE_DRIVE_FOLDER_ID	|GOOGLE_SHEET_ID	 |SHEET_NAME	|Is_Current  |
private	|xxxxxxxxx.apps.googleus...com	|                   |                   |	4_ioerjSFFDFGDFGFddL2	|6B-kdkdliDd334jja |	Sheet1	  |1           |
team    |                               |                   |                   |                       |                  |            |0           |



