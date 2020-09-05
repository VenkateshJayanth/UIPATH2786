# UIPATH2786---Hermes

1) intialize all the default setting for the sql Server.
2) Check for the folders which are more than 5 working Days and Delete them.
3) Login to the FCM website.
4)If the bot fails to login to the portal, it triggers an email to the support team.
5) Check the day is Monday or Not - i) If it is monday (3-1) fetch the last working day ii) If it is other day (-1) to the previous day & fetch the invoice accordingly.
6) Add the records to the DB for the present day.
7) Start processing the records and send the invoice to the printer in france.
8) Update the status of the job "Success","Failed","Pending" in the database.
9)Send the Summuray Report.
