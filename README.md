## Instructions

1. Clone this repository
2. Add project in Unity Hub
3. Open project. Select Ignore if asking to open in Safe Mode
4. Import FirebaseAuth package (Assets -> Import New Package -> Custom Package)
5. Go to File->Build Profiles
6. Go to Android section and select [Switch Platform] to make Android the active platform

## To Test   
1. Connect an Android device to your Computer (make sure USB debugging is enabled)
2. Select Files->Build And Run


### Note for Firebase
1. Setup your Firebase project to add Authentication and Realtime Database
2. The Firebase Unity SDK can be downloaded when you register Unity App in firebase
3. We only need the FirebaaseAuth package in the Firebase Unity SDK. Don't add the other packages.
4. Replace the googles-services.json in project with the one you downloaded from Register process of your Unity App in you Firebase project


### Other notes
1. I used the AR Mobile template to create the Unity Project so the ARScene (previously named Sample Scene) was already part of the sample code when the project was created
2. The implementation of asking permission to use camera is alreaady part of the sample code  so if you will remake the project from scratch, suggestion to use AR Mobile template to lessen ground up coding
