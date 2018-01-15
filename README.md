
# BASIC CHECKLIST 

#### Developer Accounts
1. Apple developer account.
2. Production certificates, provisioning profile(Enable iOS capabilities with production profiles as well, for example Push-Notification if using).


#### Appstore
1. Appstore app name
2. Appstore subtitle name (optional)
3. Appstore app description
4. Screenshots
5. App store icon (1024 X 1024)
6. App preview video (optional)
7. Keywords
8. Categories (need to be chosen from a drop down, good if we know in advance).
9. Bundle Identifier, Should be same with your Info.plist identifier.
10. Pricing and availability, where you can set the price and release date for your app. 
11. Copyright information like "2017 Gaurav Keshre"
12. App Review Information, Apple Review Team requires a POC who can be contacted if the App Review team has questions.
13. Temp login (if your app needs login to use always provide temp credentails to Apple Review Team for review)


#### Assets
1. Proper app icon in all required resolutions as per [HIG](https://developer.apple.com/library/content/qa/qa1686/_index.html) <br>
I use this handy [Mac App](https://itunes.apple.com/us/app/asset-catalog-creator-free/id866571115) 
2. Make sure your App icon doesn't contain "beta" word.

#### Developer
1. Proper App Version (1.0 for first release, if update increase version number to 1.1. Incase of minor releases target the build version)
2. Latest Xcode version (Alert: not to use beta or GM Seeds)
3. Upload in-app purchase content if any

#### NOTES & BEST PRACTICES:
1. A developer can submit the app and opt for "developer release" which means the app is not automatically made available to the public untill the developer choose to.

2. Don't stress too much on SKU number. It can be any string (it shohuld make sense to you)

3. choose bundle Identifier wisely <br>
Format: `com.company.app-vertical` <br>
eg: `com.apple.pages`

4. Common issues like "iOS App Ready for sale status but not appearing in the store" The delay is due to propagating your application's status across all iTunes app stores servers. it will take maximun a day so take it easy.

5. Always set developer profiles with debug mode and production/distribution profiles with release mode very first day.


#### AFTER SUBMISSION 
> _App is reviewed by apple review team_

1. It takes 3 hours to 7+ (working) days for app to be reviewed
2. For first time upload, it may take more than 3 days.


#### APP REJECTION 
>_App rejection is not a "cul-de-sac". So fix the issues and re submit_

Your app may be rejected due to following (popular) reasons
1. App has a _login_ screen but no *signup* page. (need to provide clarification)
2. Developers have used any private api (like giniee animation effect)
3. App crashes very often. 
4. Even app can face rejection after approved from Apple Review Team. Example: [Cordova hot code push] (https://github.com/Microsoft/code-push/issues/486) So please read the [Apple Store Guidlines](https://developer.apple.com/app-store/review/guidelines/)


<br><br><br>
----
<center> ```FIN``` 🏁 </center> 
<br>
