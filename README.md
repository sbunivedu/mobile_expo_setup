# Setup for Mobile App Development


## MacOS
Follow the get-started instructions on https://docs.expo.io/get-started/installation/ to install the necessary tools:
1. Install [git](https://git-scm.com/download/mac).

2. Download and install [Node.js](https://nodejs.org/) LTS, run `node -v` in Terminal afterwards to check your node version is at least `14.15.4`.

3. To install expo tool run `npm install --global expo-cli` in Terminal.

4. Install one of the recommended editors: [Atom](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-mac) or [VSCode](https://code.visualstudio.com/download).

5. Install [Watchman](https://facebook.github.io/watchman/docs/install).

6. Install [Yarn](https://classic.yarnpkg.com/en/docs/install#mac-stable).

## Windows
Follow the get-started instructions on https://docs.expo.io/get-started/installation/ to install the necessary tools:
1. Download and install [git](https://gitforwindows.org/), then you can right click on any folder to run Git Bash or Git GUI.

2. Download and install [Node.js](https://nodejs.org/) LTS, run `node -v` in Terminal afterwards to check your node version is at least `14.15.4`.

3. To install expo tool run `npm install --global expo-cli` in "Git Bash".

4. Install one of the recommended editors: [Atom](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-mac) or [VSCode](https://code.visualstudio.com/download).

5. Install [Watchman](https://facebook.github.io/watchman/docs/install).

6. Install [Yarn](https://classic.yarnpkg.com/en/docs/install#mac-stable).

## Hello World App
You also need to create an account on https://expo.io/ and install the "Expo Client" app on your phone (or other testing device) from your app store.

Follow the [get started guide](https://docs.expo.io/get-started/create-a-new-app/) to create a new app:
```
expo init my-app
cd my-app
expo start
```

You should see a QR code on your computer screen. Scanning the QR code (with the Camera app on iPhones and with the expo client app on Android phones) will launch your new app in your "expo client" app on your phone.

Change the text on your app to "Hello world from " followed by your name. To refresh you app after code change, you need to shake your device and choose "Reload" from the menu.

Take a snapshot of your screen and submit it as a proof of your work.
