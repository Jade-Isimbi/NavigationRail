# Flutter Navigation Rail Example

## Overview
This Flutter app demonstrates the use of a simple `NavigationRail` widget for side navigation, it helps in switching between the 2 section of the app which are home and settings.

## Screenshot
The screenshot of the app is in the assets folder.

## How It Works
- The app uses a `Scaffold` with a `Row` layout. The left side contains the `NavigationRail`, and the right side displays the main content.
- `selectedIndex` shows which destination (Currently selected index) is selected. 
- `onDestinationSelected` updates this index and triggers a UI update.
- The `labelType` Determines how labels appear (none, selected, all). in this case the selected destination's label is shown.
- The `destinations` property defines the icons and labels for destinations (Home and Settings).
- The main content area displays a counter and a button on the Home page, and a simple text on the Settings page.


## How to Run
1. Make sure you have [Flutter](https://flutter.dev/docs/get-started/install) installed.
2. Clone this repository or copy the project files.
3. Open a terminal in the project directory.
4. Run `flutter pub get` to fetch dependencies.
5. Run `flutter run` to launch the app on your preferred device or emulator.


---


