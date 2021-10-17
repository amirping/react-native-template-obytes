<p align="center">
    <img alt="React Native Template Obytes" src="https://user-images.githubusercontent.com/11137944/93101697-808bc580-f6a2-11ea-8ce3-482be6ca456a.png" width="200" />

</p>
<h1 align="center">
  React Native basic template
</h1>

A simple React Native Template

## ⭐ included

- ✅ Typescript by default based on official Typescript template
- ✅ Auto Generate App Icon and Splash screen
- ✅ React Navigation Pre-installed
- ✅ React Query to fetch Data
- ✅ Auth flow with react-native-mmkv to secure tokens
- ✅ A clean project structure based on our experience with React Native
- ✅ Minimal UI kit setup using restyle and configurable theme & icons using react-native-svg
- ✅ A good approach to handle forms based on react-hook-form
- ✅ A complete setup to Handle Errors
- ✅ Handel environment variables with react-native-env
- ✅ Localization
- More ...

## ▶️ Usage

```
npx react-native init MyApp --template https://github.com/amirping/react-native-basic-template
```

## ⚙️ Enable husky Git pre-hooks

Add the following script to your `packages.json` and reinstall dependencies to enable husky pre-commit using `yarn install`

```json
"scripts": {
     "postinstall": "husky install",
  },

```

## 📲 Update App Icon & Splash screen

Replace App logo template `logo.png` with your logo under `assets` folder

Run the following command to generate App icons assets :

```
yarn react-native set-icon  --path ./assets/logo.png --background "#FFF"

```

> For android icon, make sure to provide a logo with more padding and generate a new app icon for android :

```
yarn react-native set-icon  --platform android  --path ./assets/android_logo.png --background "#FFF"

```

To generate a standard splash screen using bootsplash package.

```sh
yarn react-native generate-bootsplash assets/logo.png \
  --background-color=FFFFFF \
  --logo-width=150 \
  --assets-path=assets
```

## ✏️ Custom fonts

Replace Inter.ttf font file with your fonts under `assets/fonts` folder

Run the following command to generate App icons assets :

```
yarn react-native link
```
