

##  Installing

  

**Step 1:** Download or clone this repo:


  

**Step 2:** Go to project root and execute the following command in console to get the required dependencies:

  

```

flutter pub get

```

  

**Step 3:** Add/update library to ensure flutter app works well with iOS devices

  

Firstly, we can always create flutter iOS cache via command " ** flutter precache --ios ** " in root directory of Flutter app

  

Secondly, go into ios directory via **cd ios** and perform command **pod install** to install all necessary libraries for iOS app

  

The last, as usual, open Runner.xcworkplace and configure required fields, parameters prior to running in either on Android Studio or in terminal as normal

  

**Step 4:** Install flutter app

  

```

flutter run

```

  

###  Important Notes to be aware

  

1. After successful "flutter pub get", remember go into ios, edit Podfile and add/uncomment platform line and put ít release to 12.0 or newer ( platform :ios, '12.0' ). This is the mandatory update to ensure this project runs well on iOS devices.

  

2. This FaceID works pretty well with Camera mode in "low" resolution while a bit of lag in other resolution modes. Please pay attention into this.

  

3. All flutter packages are latest up-to-date, recommend not to change anything with these packages in our production app.

  

##  Demo

  

This can be seen in below gif files (exactly these are what you can see with this app) -

  

1. https://drive.google.com/file/d/1bd0K9aYTe33cVDs2WZRuOYhOF_QsHgtl/view?usp=sharing

 