# Ozone
Installation Guide for Ozone https://www.izotope.com/en/products/mixing-mastering/ozone/

## Installing and Authorising
Ozone can be deployed using munki (https://www.munki.org). 

Then for the Authorisation folow the "Challenge/Response" guide on the iZotope site.
(http://www.izotope.com/en/support/authorization/)

## Authorise plist
Once authotised open the following folder:

~/Library/Preferences/

Inside you'll find the following plist files:

com.izotope.audioplugins.Authorizations.plist
com.izotope.audioplugins.Ozone6.Authorizations.plist
com.izotope.audioplugins.Ozone6App.Authorizations.plist

These need to be copied into:

/Library/Preferences/

Once copied run the fixpermissions.sh to change the permission to allow everyone Read-Only access.


## Finished
Now anyone logging on can use Ozone.
