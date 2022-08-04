# WeekendVibes

 The vibes app

 ## ✨ Requirements
* Any Operating System (ie. MacOS X, Linux, Windows)
* Any IDE with Flutter SDK installed (ie. IntelliJ, Android Studio, VSCode etc)
* A little knowledge of Dart and Flutter
* A brain to think 🤓🤓

## Features
 * Custom photo feed 
 * Post photo posts from camera or gallery
   * Like posts
   * Comment on posts
        * View all comments on a post
 * Search for users
 * Realtime Messaging and Sending images
 * Deleting Posts
 * Profile Pages
   * Change profile picture
   * Change username
   * Follow / Unfollow Users
   * Change image view from grid layout to feed layout
   * Add your own bio
 * Notifications Feed showing recent likes / comments of your posts + new followers
 * Swipe to delete notification
 * Dark Mode Support
 * Used Provider to manage state
 
  ![Project banner with app screenshots](https://user-images.githubusercontent.com/8056274/126907246-9fa5c3c7-6bf1-4733-b36b-7b35d2db0bf6.jpg)
 
## Installation

#### 1. [Setup Flutter](https://flutter.dev/docs/get-started/install)

#### 2. Clone the repo

#### 3. Setup the firebase app

- You'll need to create a Firebase instance. Follow the instructions at https://console.firebase.google.com.
- Once your Firebase instance is created, you'll need to enable Google authentication.

* Go to the Firebase Console for your new instance.
* Click "Authentication" in the left-hand menu
* Click the "sign-in method" tab
* Click "Email and Password" and enable it
* Create an app within your Firebase instance for Android, with package name com.yourcompany.news
* Run the following command to get your SHA-1 key:

```
keytool -exportcert -list -v \
-alias androiddebugkey -keystore ~/.android/debug.keystore
```

* In the Firebase console, in the settings of your Android app, add your SHA-1 key by clicking "Add Fingerprint".
* Follow instructions to download google-services.json
* place `google-services.json` into `/android/app/`.

- (skip if not running on iOS)

* Create an app within your Firebase instance for iOS, with your app package name
* Follow instructions to download GoogleService-Info.plist
* Open XCode, right click the Runner folder, select the "Add Files to 'Runner'" menu, and select the GoogleService-Info.plist file to add it to /ios/Runner in XCode
* Open /ios/Runner/Info.plist in a text editor. Locate the CFBundleURLSchemes key. The second item in the array value of this key is specific to the Firebase instance. Replace it with the value for REVERSED_CLIENT_ID from GoogleService-Info.plist

Double check install instructions for both
   - Google Auth Plugin
     - https://pub.dartlang.org/packages/firebase_auth
   - Firestore Plugin
     -  https://pub.dartlang.org/packages/cloud_firestore

- You can also use my firebase if you wish

# What's Next?
 - [] Animations(liking image)
 - [] Stories['under development]
 - [] Saving posts
 - [] Video Calling ['under development']

1.Music Page
![Music Example Image 1](https://user-images.githubusercontent.com/33089347/182942995-640b116d-95e9-4934-96c7-92bb5f3de42b.PNG)
![Sticker Example Image 1](https://user-images.githubusercontent.com/33089347/182943059-b2af090c-d86a-4124-87ec-09b20f954267.PNG)
![Style 2 (Image 1) ](https://user-images.githubusercontent.com/33089347/182943068-96dbae42-9f0c-4a50-a2f3-068eb8718f48.PNG)
![Home Page Image 1](https://user-images.githubusercontent.com/33089347/182943074-a4cc094f-0dea-4601-831d-99dd3f591888.PNG)
![Pricing Example Image 1](https://user-images.githubusercontent.com/33089347/182943190-bbe481db-478c-43c0-9c5d-f735948e18da.PNG)
