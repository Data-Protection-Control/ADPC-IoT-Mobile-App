# ADPC IoT Mobile App

## Summary

The ADPC IoT Mobile App is a prototype application designed to facilitate interaction with IoT devices via Bluetooth Low Energy (BLE). It enables users to send and withdraw consents for data privacy directly from their mobile devices. Featuring a user-friendly interface that aligns with the design standards of modern mobile applications, the app enhances user interaction with IoT devices. Additionally, it explores the integration of Large Language Models (LLMs) through OpenAI's ChatGPT API, initially focusing on simplifying consent requests from IoT devices. The app's potential future expansions could further leverage LLMs to unlock new capabilities. The ADPC IoT Mobile App supports both iOS and Android platforms, ensuring a wide reach across different devices.

## Installation Requirements

Before you can run the ADPC IoT Mobile App, ensure you have the following installed:

- **Expo CLI**: Essential for running and testing the app.
- **Expo Go**: Install this on your phone for live testing.
- **NPM**: Node Package Manager, crucial for managing the app's dependencies.
- **React Native**: The framework used for developing the application.

### Setting Up Your Environment

Install Node.js and NPM: Download and install Node.js from its official website. NPM comes bundled with Node.js.

Expo CLI Installation:

```bash
npm install -g expo-cli
``` 

Download Expo Go: Navigate to your respective app store on your mobile device and search for "Expo Go" to download and install it.

#### Clone the Project:
Clone the repository to your local machine using:

```bash
git clone <repository-url>
```

#### Install Project Dependencies: 
Navigate to the project directory and run:

```bash
npm install
```

This command installs all necessary dependencies listed in the project's package.json file.

## Testing the App

To test the app on your development environment, you can use the following commands:

For Android:
```bash
npx expo run:android
```

For iOS:
```bash
npx expo run:ios
```

## Testing on Emulators

To simulate the app on virtual devices, ensure you have:

Android Studio: For Android emulator setup.
Xcode: For iOS simulator setup.
Note: For testing Bluetooth capabilities, a physical device is necessary, as emulators do not emulate Bluetooth functionality.

## Future Research and Development

Future iterations of the ADPC IoT Mobile App may explore additional uses of Large Language Models to enhance the interaction between users and IoT devices, capitalizing on the vast potential of these technologies for improving user experience and consent management.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.
