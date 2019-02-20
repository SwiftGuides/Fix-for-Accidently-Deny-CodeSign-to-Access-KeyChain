# Fix-for-Accidently-Deny-CodeSign-to-Access-KeyChain
This Simple Guide will help to to Ask CodeSign Access Keychain Permission Again and You can Enter MAC User Account password to Allow access


Source :- https://stackoverflow.com/a/47771360/10422074

### Solution Steps :-

1. If that error occurs, only you have to do is just lock the keychain (click on lock in the left upper most corner).
2. Now Build Again. It will ask to unlock again like first time and Let you to choose always allow or allow or deny in Codesign keychain access.
3. Just type account (Mac User account) password and click on always allow. Then project will build successfully.
4. Voila !! It will work now
