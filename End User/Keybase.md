# Keybase

KeyBase is a technology that uses PGP private and public keys to validate you are the person who both owns the KeyBase account and your social accounts.

It works by encrypting a message with your private key, then you post that message to your social account.  KeyBase will then ues your public key to validate that you do own the target account.

##  PGP

We use a similar pattern of authentication between the privacy platform and remote applications.  This allows us to validate a remote application is who it says it is and likewise, they can be assured that any messages did originate from the privacy platform.