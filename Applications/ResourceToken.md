#   Resource Tokens

A resource token is a token that allows an application or user to gain access to a data subjects information.

##  Expired Tokens

Tokens are only valid for a small period of time before they expire and will not be able to be used to gain access to a data subject's data.

##  Revoked Tokens

At any time a data subject can delete/revoke a resource token.  When this occurs, any request tied to that token will not be able to be processed (or re-processed in the case of [ReDelete](ReDelete.md).

##  Deleted objects

Note that a data subject may delete a data object that is included in a resource token at any point.