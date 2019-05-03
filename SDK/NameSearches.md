# Name Searches

Searching based off names may seem like a reasonable request, but as you get further into the realities of executing the queries against your source applications you will realize that it just isn't a good idea.

##  Issues with Name searches

Searching based off name can present many problems.  Just a few include:

-   People with matching first and last name
-   People with unicode characters in their name (your application removed them)
-   Searching based on an unverified name can cause data leakages

In general, name-based data should only be used as a secondary backup to some other key-based data point (such as email).