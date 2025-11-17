# Welcome to your Expo app 👋

## Build commands

- Pre build apps without EAS
<!-- cspell:words prebuild -->

npx expo prebuild --clean
npx expo prebuild --platform ios
npx expo prebuild --platform android

npx expo run:ios --device
npx expo run:android --device

eas build --platform ios --profile production --local
eas build --platform android --profile production --local
eas build --platform android --auto-submit

<!-- Android profile preview -->
eas build -p android --profile preview
