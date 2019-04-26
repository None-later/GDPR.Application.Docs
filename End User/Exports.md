# Exports

When you make a query request to a company or application, they will execute that query against every application and return a common format, machine readable export of that data.  This data could be in any number of formats with JSON being one of the most common.  In some cases, the data may actually be packaged using the applications tool of choice (for example, Office 365 has a .NET package wrapper to gain access to the Azure Storage location for the export).

##  JSON Exports

When the export is a JSON file, we provide a built in tool for browsing that data and determining what action you would like to take next.  Those actions could be to do nothing, delete it or update it.  Keep in mind that not all applications will support the notion of "update".

If you choose to send a delete request and the data is in JSON record format, you will be presented with the records in the remote system such that you can select what data you want deleted.  You can also simply "delete all" and anything that does not have a policy against it and is avilable to be deleted, will be removed from the target system.

##  Zip Exports

Zip exports will not have a viewer and will require you to download the file and review the information in it.  These types of files are not record based and will require a manual deletion process by the company and application records managers.  These can take significantly longer to process and is solely determined by the owners of those applications and not automated by the privacy platform.

##  Custom tool exports

These types of exports will require you to download a tool of some sort to then download the search results from your query.  Similar to Zip file exports, you will need to review these and then decide what information you would like deleted from the target system.

