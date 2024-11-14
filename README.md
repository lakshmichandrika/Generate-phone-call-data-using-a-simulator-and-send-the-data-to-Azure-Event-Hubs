# Generate-phone-call-data-using-a-simulator-and-send-the-data-to-Azure-Event-Hubs

1.create an event hub namespace-event hub-policy

2.Create a Stream Analytics job

3.Stream Analytics job-storage account settings-click on select blob/adls from subscription-save

4.Configure job input-eventhub-authentication mode(i.e,change to connection string)

5.in synapse -create a dedicated sql table(check by running,no data will be present now)

6.Configure job output-synapse-authentication mode(i.e,change to connection string)-give user name and password of synapse-give table name we just created

7.download the generator folder-in config -give event hub name,connection string(i.e,created event hub policy-where primary connection string is present)

8.copy the generator path-in the search of system type "cmd" -type cd &path(i.e,cd c:\user----) -enter

9.command to start the job type .\telcodatagen.exe 1000 0.2 2

10.go to stream analytics job-query-(i.e,stream.sql file)

11.go to stream analytics job -start

12.now go to syanpse and check the table-you can see data-if you refreh and check-the data goes on increasing.

13.stop the job after the work is done












