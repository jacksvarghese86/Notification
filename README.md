# Notification

This is a sample project which details firebase cloud messaging(Notifications) in Android.
This also shows how to send notifications from one application to another application.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

Since you are here, i am assuming you have the necessary tools to build an Android app.
If not please follow below tutorial. 
https://developer.android.com/training/basics/firstapp/

### Firebase account
Firebase is Google's mobile platform that helps you quickly develop high-quality apps and grow your business.
Firebase provides tons of services, the one that we are particularly interested in is 'Cloud Messaging' or in layman terms 'Notifications'. To access firebase tools and services we need to create a Firebase account and link our app to that accouint.
#### Steps
      1. Create a firebase account and login. (https://console.firebase.google.com)
      2. Add a new project. Click on the android icon to link our application to the firebase account.
      3. Use package name as com.appcart.notification. (This is the package name currently used in the given source code.)
      4. Download google-services.json file and replace the existing one (~/Notification/app/google-services.json).
      5. Now our application is connected to firebase account.
      6. Choose cloud messaging option from the left pane of firebase console and start sending your first notification
      
## Next steps
1. Trigger notification from another android application.
2. Trigger notification from a server
