
# Schoolbook

Schoolbook is a mobile application built using Cordova, designed to help students manage their education


## Installation

To run the project locally, you'll need to have [Node.js](https://nodejs.org/) and [Cordova](https://cordova.apache.org/) installed.

### Prerequisites

1. Install Cordova globally:
   ```bash
   npm install -g cordova
   ```

2. Install platform-specific SDKs (Android/iOS) as required for the build.

### Clone the Repository

Clone this project to your local machine:

```bash
git clone https://github.com/croodles/Schoolbook.git
cd Schoolbook
```

### Add Platforms

You can add Android and iOS platforms using Cordova.

For Android:
```bash
cordova platform add android
```

For iOS:
```bash
cordova platform add ios
```

### Build the App

Build the application for the added platforms:

For Android:
```bash
cordova build android
```

For iOS:
```bash
cordova build ios
```

### Running the App

You can run the app on an emulator or a connected device:

For Android:
```bash
cordova run android
```

For iOS:
```bash
cordova run ios
```

## File Structure

- **www/**: This folder contains the HTML, CSS, and JavaScript files for the frontend.
- **platforms/**: Generated code for specific platforms like Android and iOS.
- **config.xml**: Configuration file for Cordova.

## Technologies Used

- **Cordova**: For cross-platform mobile development.
- **HTML5, CSS3, JavaScript**: Frontend technologies.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
