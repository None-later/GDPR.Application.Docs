# Discovery

Discovery is the process of querying the application to find all data subjects.  If your application does not support the ability to send "Create" messages, when a new data subject is created then you will need to periodically submit a "Discover" request.  

##  Change Dates

Most applications support the ability to do a "Change Date" based "Discovery". The Change Date is the date that you are looking to filter the results of the "Discovery" query.  Anything created or modified after the change date will be ingested into the system.

If an application does not support a change date, then the "Discover" request will have to enumerate all the records in the application storage.  This can be a very expensive and resource intensive operation so you should use it sparingly when a "Change Date" is not supported.