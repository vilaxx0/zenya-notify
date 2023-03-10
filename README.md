# Zenya Notify - Location-based notifications

This is a prototype flutter application developed for the company "Zenya" as a part of the Mobile Development minor program at the Fontys university. The application allows users to set push notifications for their current location within a specific radius. The purpose of the application is to provide a solution for businesses to target customers in a particular location with relevant push notifications.

## Getting Started

To get started with the application, you need to have Flutter installed on your machine. If you don't have Flutter installed yet, follow the installation instructions for your operating system on the official website.

After you have installed Flutter, follow these steps:

1. Clone the repository to your local machine by running the following command in your terminal or command prompt:

```bash
git clone https://github.com/vilaxx0/zenya-notify.git
```

2. Open the project in your preferred IDE.
3. Install the dependencies by running the following command in your terminal or command prompt:

```bash
flutter pub get
```

4. Connect your Android or iOS device to your computer, or start an emulator. Make sure that the device or emulator is properly configured for development and is visible to Flutter by running the following command:

```bash
flutter devices
```

5. Run the application on the device or emulator by running the following command in your terminal or IDE:

```bash
flutter run --no-sound-null-safety
```

Note that the **--no-sound-null-safety** flag is necessary because the project is not yet migrated to null safety. This flag allows you to run the application without null safety checks, but keep in mind that it may lead to runtime errors if you try to use null values.

## Features

- Set push notifications for the current location within a specified radius.
- Use text-to-speech functionality to create push notification messages.
- Simple and easy-to-use user interface.
- Supports both Android and iOS platforms.

## Limitations

This is just a prototype application and has several limitations, including:

- The push notification functionality is limited to the device on which the app is installed.
- The location detection functionality may not be accurate due to limitations of the device sensors.
- The text-to-speech functionality may not be supported on all devices.

## Contributions

This prototype application was developed by Vilius Bučinskas as part of an academic project, and we are not accepting contributions at this time.
