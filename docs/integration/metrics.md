# How can I track LinkedIn automation metrics within my analytics dashboard?

Yes. You can acomplish that via and Events dump

## What are events
Events are occasions that happens in your campaign such as
- Chat messages
- Connection RRequets
- Errors
- Replied to Chat
- No Intrest
- Queued etc 

When they take place they are recorded in the database and also forwaded to all listening webhooks.

## How to export events

Select the desired campaign from the dropdown

![Click Campaign from Selector](/images/export-csv-01.png)

You will be taken to campaign page. From here you want to click the **DUMP EVENTS** button

![Export CSV](/images/export-events_02.png)

This will ask you for the email which will recieve the exported file.

![Export CSV](/images/export-events_03.png)

Edit the email if you need to, then click send then click send.

This will create a task in the background to export the data. After its its finished you wil recieve an email with the attached CSV file.