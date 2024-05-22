# Flight Tracking App

## Introduction

This project is a Flight Tracking Application that provides real-time flight information.

---------------------------------
## Prerequisites

This is a React Native project so requires working react native environment to run.

[React Native](https://reactnative.dev/docs/environment-setup)

[Visual Studio Code](https://reactnative.dev/docs/environment-setup)

[Android Studio ](https://docs.expo.dev/get-started/set-up-your-environment/?platform=android&device=simulated&mode=development-build)

[Xcode](https://docs.expo.dev/get-started/set-up-your-environment/?platform=ios&device=simulated&mode=development-build)

[Ignite CLI](https://github.com/infinitered/ignite)

-----------------------------------------------
## Project Setup

Clone the repository and install dependencies:

```
git clone https://github.com/aiyubinx/Flight-Tracking-App.git
cd Flight-Tracking-App
Install node modules - yarn install
```

-----------------------------------------------
## Build and Run Application

To run project use NPM scripts or run below command

```
npx expo start --android
npx expo start --ios
```

-----------------------------------------------
## Project Structure

```
app
├── components
├── config
├── i18n
├── models - Models to store api data
├── navigators 
├── screens - Business logic
├── services - Api services
├── theme - App theme files
├── utils 
└── app.tsx - Application entry point

```

---------------------------------------------------
## API Routes

To get Flight Information by flight_icao number used this api - 
```
http://api.aviationstack.com/v1/flights?access_key=1ef5aa8c887a3beed47f6fbf0ace4b11&flight_status=active&flight_icao=${fightIcaoNo}
```
  
