# Dice Roll Application

This is a simple Flutter application that simulates a dice roll.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Flutter and Dart installed on your machine. You can download them from [here](https://flutter.dev/docs/get-started/install).

### Installing

1. Clone the repository
```bash
git clone https://github.com/dotcomaki/diceapp
```
2. Navigate to the project directory
```bash
cd diceapp
```
3. Get the dependencies
```bash
flutter pub get
```
4. Run the app
```bash
flutter run
```

## Usage

The application simulates a dice roll. When you run the app, it displays a gradient container with two colors. The colors are defined in the `GradientContainer` widget. The dice roll is simulated by generating a random number and displaying the corresponding dice image.

## Troubleshooting

If you encounter any issues with loading assets, ensure that:

1. The asset is properly declared in the `pubspec.yaml` file.
2. The asset is in the correct location.
3. The asset's filename matches exactly with what you have in your code, including the case.
4. If you've added new assets to your project, you might need to stop and restart your app for the new assets to be recognized.
5. If the asset is not properly bundled with the app, try running `flutter clean` in your terminal to clean your build, then rebuild your app.
