# CivicHeart
![CivicHeartiOSScreens](https://github.com/shahjacobb/DevFest24-at-Columbia/blob/main/CivicHeartBanner.png?raw=true)
## Front End

### Instructions for Windows
1. Run npm install to download all the packages in `packages.json.` This project requires the Expo SDK, so you'll need Expo Go to be able to emulate the app on your iPhone (you can't build iOS Apps on WinOS)
2. `App.js` is in the root directory, so just run `npx expo start`
3. Scan the QR code with your phone's camera, and if the app is installed, it'll redirect you. Press R to reload the build if you make a change (if it doesn't automatically already get updated)

### Instructions for Mac
1. Download XCode (and most importantly, the Xcode Command Line Tools
2. Run `npx expo start` -- you can run the emulator for any supported iPhone right on macOS without needing to download the Expo app on the iPhone
## Back End
1. Navigate the terminal into `/server`
2. Run `npm install` to install all Node dependencies.
3. Requires ".env" file information
```
REACT_APP_MONGODB_KEY = mongodb+srv://devfest24:devfest24@devfest24.nkeqmxs.mongodb.net/?retryWrites=true&w=majority
```
3. Run `node server.js` to begin the connection to the MongoDB database.

## Tools

- Figma
- React Native & CSS
- Javascript
- MongoDB based in GCP

### Frameworks
- Expo Go
- Express

### App Design
- Figma App Prototype:
[Figma](https://www.figma.com/file/tpOECeHhvKrjsGEklITL25/DevFest-2024---CivicHeart?type=design&node-id=31%3A75&mode=design&t=emQWfnPzwtat6PdZ-1)
<img src="https://cdn.discordapp.com/attachments/1200628145502568458/1203588385852358716/Untitled_Notebook_3-1.jpg" width="400" alt="UserFlowSketch">

