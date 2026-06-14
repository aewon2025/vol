UPLOADING CSV CREDENTIALS
==========================


Note  you may have upto two accounts' credentials saved on the app (Private, Team), but only one active at a time.  

-  If user is authenticating using OAuth. * Info required:  

        -  google oauth client id, the google folder id, google sheet id and sheet tab name  

-  If user is authenticating using service account. * Info required:  

        -  the drive client email, drive private key, google folder id, google sheet id, and sheet tab name

*Instead of entering the credentials manually on the Private/Team account u may add 1 or both cred to a csv file. Below is the template to follow.  

The example below represents the content of a csv file where user is authenticating using OAuth:

Account	|GOOGLE_OAUTH_CLIENT_ID	        |DRIVE_CLIENT_EMAIL	|DRIVE_PRIVATE_KEY	|GOOGLE_DRIVE_FOLDER_ID	|GOOGLE_SHEET_ID	 |SHEET_NAME	|Is_Current  |
private	|xxxxxxxxx.apps.googleus...com	|                   |                   |	4_ioerjSFFDFGDFGFddL2	|6B-kdkdliDd334jja |	Sheet1	  |1           |
team    |                               |                   |                   |                       |                  |            |0           |

The example below represents the content of a csv file where user is authenticating using OAuth:

Account	|GOOGLE_OAUTH_CLIENT_ID	        |DRIVE_CLIENT_EMAIL	|DRIVE_PRIVATE_KEY	|GOOGLE_DRIVE_FOLDER_ID	|GOOGLE_SHEET_ID	 |SHEET_NAME	|Is_Current  |
private	|xxxxxxxxx.apps.googleus...com	|                   |                   |	4_ioerjSFFDFGDFGFddL2	|6B-kdkdliDd334jja |	Sheet1	  |1           |
team    |                               |                   |                   |                       |                  |            |0           |

