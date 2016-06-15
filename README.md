siebel-salesforce
=================

Siebel to Salesforce integration (batch, realtime, 2 way sync)

Use Case
The hypothetical customer is migrating from their existing CRM (Siebel) to the new CRM (Salesforce). The two will co-exist during the migration/co-exist phase till Siebel gets deprecated. Till then all records in SFDC should exist (near real time sync) in Siebel and all records created/updated in Siebel should be synced in SFDC. For this, there has to be a one-time ETL task of loading all records in Siebel to SFDC. For the purpose of this demo, we will only show the ‘contacts’ data being synced.

High-level Steps
1. Show one time ETL job loading all contact data from existing CRM (Siebel) to new CRM (Salesforce), using the Batch feature.
2. Show incremental updates to SFDC contacts synced in real-time to Siebel using Streaming API.
3. Show incremental updates to Siebel contacts synced in real-time to SFDC using Poll and Watermarks.

Projects:
https://github.com/rupeshr/siebel-salesforce

Siebel-SFDC-Batch (use case 1)
Siebel-SFDC-Realtime (use case 2)
SFDC-Siebel-Streaming (use case 3)

Detailed script for executing projects (requires permission):
https://docs.google.com/a/mulesoft.com/document/d/1f0Vkzsn4aWgIu7a4mJK3HOS0IGDaPihcvrqmTX-P8wQ/edit#

UPDATE: Newer versions of Siebel-Salesforce integration apps are now officially available as MuleSoft certified templates on Anypoint Exchange. You can download the templates (Mule app) for free and run it on Anypoint Studio. Make sure you change the connection properties to point to your instances. 

https://www.mulesoft.com/exchange#!/?searchTerm=siebel&filters=Salesforce&sortBy=rating

