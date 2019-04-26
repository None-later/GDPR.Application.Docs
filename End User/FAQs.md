# Frequently Asked Questions (FAQs)

Here are some common questions we are asked about the platform.  Feel free to email us at support@privacycentral.com if their is something we do not address here.

##  Where is my data stored?

### In the Platform

The moment you create an account we will have an unverified email account for you.  It is up to you to enter what data you feel comfortable adding and verifing.  You can reference our security practices to see how we secure your data.  Any data you enter in the platform resides in our encrypted databases in our Microsoft Azure cloud tenant.  

### In External Company's Applications

Companies also have your data in their cloud and on-premises applications.  Their process for securing your data is outside of our control and any inquires about that should be directed to those specific entities through their security or privacy officer.

When you submit a request to a company, you must provide them with verified information so they can search for your data.  This process exists even if they are not using the privacy platform.  By using the platform, we as a third party are able to audit and ensuring that companies are responding to your requests in a timely manner, as well as helping them to reduce costs of handling your requests.

##  How do you secure my data?

The data your provide to use is fully encrypted using AES256 encryption with rolling keys.  This basically means we could post our database to the internet and it would take several years and an immense amount of super computing power for a bad actor (hacker) to get any meaningful data out.  With human life expectancy of 100 years, the data would be worthless by the time they accomplished the task.

Additionlly, we use strong workload factor hashing with rolling salts to hash your data so we can do comparisons to determine if a company has your data and to then notify you of such.

You also have the option to "Bring Your Own Key" (BYOK).  By doing this, you will encrypt the data such that we can't even decrypt it for request submissions.  The platform will only be able to process requests on your behalf when you have logged in and entered your keypin.  The keypin is stored in memory and we do not log or record it for future processing.  Once your session ends, we again will not be able to do anything with your account other than delete it completely provided your account meets the deletion requirements.

##  Why can't I submit certain request types to a company or application?

Not all applications support the ability to perform all requests.  Some applications are very old and were never designed to support actions such as "Hold".  In some cases, the application stub may be very new and the code for that particular action has not been written yet by us or the application owner.

All applications are required to support the ability for "Query" and "Delete".  Other activities like "Update" and "Hold" could possibly never be implemented.

##  How does data flow between the platform and remote applications?

When you submit a request to a company or an application, you select the data you would like to send to them for request purposes.  It is best to limit the data you send to what you know they have on you.  For example, if you have 4-5 different email accounts, yet you know the company or application only has one of those, then only send that email for processing.

When we send a request to an application, it recieves a resource token that is only valid for a certain period of time and only specific to the resources you allowed.  The application will make a request to the platform using this token to retrieve the information and then process your request.

When an application has completed the request, they will send us back in the information such that either they host the exported data, or we host it.  In the case where they host the exported content, we will encrypt the url in the request and when you log in, you will see the unencrypted link to the export. In the case where we host the exported data, it will be placed in a secure Azure storage account with the link being encrypted similar to your personal data.  In some cases, this data export is compressed and encrypted with a password such that only you would be able to retrieve it.

##  When I submit a delete request, not all data is deleted, why?

Due to legal requirements, not all data can be deleted.  For example, if you have a contract with a company that expires 3 years from now, that anything relating to that contract must be retained for those 3 years, plus any legal retention period (which could be up to 7 years in some cases).  Companies are able to add policies to their applications record types that would describe to you the retenion requirements of the data for your reference.  This is a voluntary process and not all companies will provide this.

##  Why can't I delete my account?

TODO