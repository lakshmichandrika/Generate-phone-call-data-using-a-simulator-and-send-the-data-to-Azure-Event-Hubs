# Generate-phone-call-data-using-a-simulator-and-send-the-data-to-Azure-Event-Hubs

1. Generate sample phone call data using a simulator and send the data to Azure Event Hubs.
2
3. 
4. Ingest data into Synapse Analytics dedicated SQL pool using the query.
5. Start the stream analytics Job.
6. Check data in the dedicated SQL pool.

create an event hub namespace-event hub-policy

Create a Stream Analytics job

Configure job input-eventhub-authentication mode(i.e,change to connection string)

in synapse -create a dedicated sql table(check by running,no data will be present now)

Configure job output-synapse-authentication mode(i.e,change to connection string)-give user name and password of synapse-give table name we just created
