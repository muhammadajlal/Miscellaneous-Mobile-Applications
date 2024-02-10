# Mobile-Application-Development-Labs

## 1. Firebase Analytics Mobile Application
Firebase Analytics is a tool provided by Google's Firebase platform to help app developers measure user engagement, retention, and in-app behavior. It allows developers to track events, user properties, and conversions, which can be analyzed to gain insights into app usage and user behavior. With Firebase Analytics, developers can track custom events specific to their app, such as user sign-ups or purchases, and use this data to optimize the user experience and improve their app's performance. It also provides real-time data and analytics, which can be viewed through the Firebase console.

### Description

The Firebase Analytics App is an Android application developed in Android Studio. The app includes two buttons that record different events when clicked by the user. The app is integrated with Firebase Analytics to track these events.

### Features

1. **Set up Firebase Analytics**: The app is connected to Firebase. A new project was created in the Firebase console, the Firebase configuration file was added to the Android project, the necessary dependencies were added to the app-level `build.gradle` file, and Firebase was initialized in the app.

2. **Create Two Buttons**: The app includes two buttons that record different events when clicked by the user. The layout for the two buttons was created in XML, the `onClickListener` for each button was defined in Java, and the Firebase Analytics API was used to log events when the buttons are clicked.

3. **Test the App**: The app was built and run on a device or emulator, and the Firebase Analytics console was checked for event data to verify that events are being recorded.

## 2. Firebase Realtime Database Mobile Application

Firebase Realtime Database is a cloud-hosted NoSQL database that allows developers to store and sync data between clients and servers in real-time. It is designed to handle data that is frequently updated and requires low-latency access from multiple clients. The database can be accessed using a variety of platforms, including Android, iOS, and web applications. An app that reads and writes data to Firebase Realtime Database is designed to allow users to store and retrieve data in real-time from the cloud-hosted NoSQL database. It enables developers to create applications that can handle frequently updated data and low-latency access from multiple clients. The app can be used for a wide range of purposes, from simple note-taking and task management to more complex projects, such as social media platforms and online marketplaces. With Firebase, developers can easily integrate a real-time database into their Android applications and provide users with a seamless and reliable experience.

### Description

The Firebase Realtime Database App is an Android application developed in Android Studio using Java. The app allows users to add, retrieve, update, and delete data from a Firebase Realtime Database.

### Features

1. **Setting Up Firebase Realtime Database**: The app is connected to a Firebase project and has Firebase Realtime Database enabled. The necessary Firebase SDK dependencies were added to the Android Studio project, and the Firebase Realtime Database security rules were configured to allow read and write access to authorized users.

2. **Implementing Data Model and Database Operations**: A Java class was defined to represent the data stored in the Firebase Realtime Database. Methods were created for adding, updating, deleting, and retrieving data from the database. User interface components were implemented to allow users to interact with the database.

3. **Testing the App**: The app's ability to read and write data to the Firebase Realtime Database was tested. It was verified that the app can add, update, and delete data as expected.

## 3. Camera/Gallery Photo-Based Mobile Application
The **camera** on an Android device allows users to capture photos and videos using their device's camera hardware. The Android SDK provides a camera API that enables developers to access the device&#39;s camera functionality and capture media content from the camera. With the camera API, developers can specify camera settings, such as image resolution, flash modes, and
autofocus modes, and capture media content using an intent or a camera preview. 

The **photo gallery** is an app on Android devices that allows users to view, organize, and share their photos and videos. The photo gallery stores all media files, including images and videos, in a device's local storage. Developers can access the photo gallery and retrieve images and videos using the Android SDK. Android provides a media content provider API that allows developers to access the photo gallery's database and retrieve media content by URI.

## Description

The Camera/Gallery Photo-Based App is an Android application developed in Android Studio using Java. The app allows users to take a photo using the device's camera or select a photo from the gallery. The selected photo is then displayed in the app.

## Features

1. **Camera Functionality**: The app has the CAMERA permission added to the application's manifest file. It checks for permission to use the camera in the code using the `checkSelfPermission()` method. If permission has not been granted, it requests it from the user using the `requestPermissions()` method. The camera is launched using an intent with the `ACTION_IMAGE_CAPTURE` action. The app waits for the intent result, retrieves the photo taken by the camera, and displays the photo in the app using an ImageView or other appropriate UI element.

2. **Photo Gallery Functionality**: The app has the `READ_EXTERNAL_STORAGE` permission added to the application's manifest file. It checks for permission to read from the gallery in the code using the `checkSelfPermission()` method. If permission has not been granted, it requests it from the user using the `requestPermissions()` method. The photo gallery is launched using an intent with the `ACTION_PICK` action. The app waits for the intent result, retrieves the selected photo, and displays the photo in the app using an ImageView or other appropriate UI element.

3. **Testing and Debugging**: The app has been tested on a device or emulator for its camera and photo gallery functionality. Any issues that arose, such as null intent results or incorrect photo display, were debugged.

## 4. Sensors Based Mobile Application

## Description

The Sensors-Based App is an Android application developed in Android Studio using Java. The app implements three different sensors (accelerometer, light, and pressure sensors) and displays the current sensor readings, updating them in real time.

## Features

1. **UI Elements**: The app includes UI elements such as text views or progress bars to display the sensor readings.

2. **Sensor Implementation**: The app uses the `SensorManager` class to access the sensors and register for sensor events. It implements the `onSensorChanged()` method to retrieve and update the sensor readings. The UI elements are updated to display the sensor readings in real time.

3. **Testing and Debugging**: The app has been tested on a device or emulator for its sensor readings. Any issues that arose, such as null sensor values or incorrect sensor readings, were debugged.


## Setup

To set up any of the above-mentioned mobile applications on your local machine, follow these steps:

1. **Clone the repository**: Clone the repository to your local machine using the command `git clone https://github.com/muhammadajlal/Miscellaneous-Mobile-Applications.git`.

2. **Open the project in Android Studio**: Navigate to the directory where you cloned the repository and open any of the projects in Android Studio.

3. **Run the app**: Click on the `Run` button in Android Studio to build and run the app. You can choose to run the app on an emulator or on an Android device connected to your computer.
   
4. **Connect the app to Firebase**: Only for the Firebase-related applications please follow the instructions in the Firebase documentation to connect the app to Firebase.

## Contributing

Contributions are welcome! Please read the contributing guidelines before getting started.

## License

This project is open-source and it's free to use for academic purposes.
