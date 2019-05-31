# Data Verification

The following are the various types of data you can enter into the privacy platform.  Not all of these may be active for your instance and not all will be supported across all applications as a search parameter.

-   [Addresses](Profile_Addresses.md)
-   [Biometrics](Profile_Biometrics.md)
-   [Dna](Profile_Dna.md)
-   [Emails](Profile_Emails.md)
-   [Government identity](Profile_GovernmentIdentity.md)
-   [Phones](Profile_Phones.md)
-   [Social Identity](Profile_SocialIdentity.md)

## Current Active Data Types

The following data types are enabled in the system as a currently verifiable type.  We provide a bit more information about how we validate each of the various types.

### Addresses

We normalize your address data via many different address APIs and can even pick up your new address through the US Postal Service if you have filed for address forwarding.  

Once we have your properly formatted address, we will then validate it thorugh one of two means:

-   Credit Card Address Verification Service (AVS): This will cause a small charge to your credit card and will validate the address you entered is tied to a credit card.  This process can verify your address almost instantaneously
-   Postcard:  We will send a post card to your address (typically within 3-5 days) with a verification code that you will need to enter in order to validate your address.

### Emails

We will send a verification code to your email which you will need to enter into the web UI.

### Government Identity

You will be required to upload the document which we will then verify if valid.  Some forms of identity will tkae longer than others to verify and may have a small charge related to it.

### Phones

We can both call you with a code or send you a text message with a code to verify your address.  Both of which would need to be entered into the web UI or via our IVR system.

### Social Identity

We utilize KeyBase to validate social identities.  You can also utilize OAuth to validate your identities, but this is a more manual process on your part and would require you to give the privacy platform permissions to perform a query for a valid account.

##  Future Data Types

The following types of data are still in their infancy when it comes to data subject requests.  It is possible they may never become a searchable data type, but as technology is always evolving, this could change.

##  Biometrics

Some biometric types are easier than others to verify (only in the cases that a standard format exists) and we expect items like facial to be a standard part of the verification data profile.  You can refrence the types of biometric types [here](Profile_Biometrics.md).

##  Dna

Dna is currently outside the scope of the privacy platform, but we anticipate it to be included in future applications very soon.