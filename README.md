# googleCalendar-Kohana


#Requirements :

1. Googleapiclient is already installed using composer inside the project folder.
2. Credentials.json, tokens and oauth2authentication(php) are inside the project.
3. Authorized URL for redirection is made as http://localhost (during the process of enabling the google api).
4. Calendar Events are inserted into the database (googleevents) and table name -> [googlecalendars]=>[emailID,eventName,eventTime] (emailID and eventName) are the composite primary key.

