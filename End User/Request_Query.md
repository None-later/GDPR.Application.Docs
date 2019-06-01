# Query

Every application must support this DSAP action.  It will not be listed in the privacy platform if it does not have this ability.  

Query is a basic mandatory operation that every application has to be able to execute.  The data returned can be in the form of "records" or a application specific format/download link.

##  Performing a Query

You can perform a query by searching for a tenant and then sending a tenant-wide request, or sending a request to each application.  Because tenants can have 10s to 100s of applications, you may find it easier to submit a request as a "single" workflow request.