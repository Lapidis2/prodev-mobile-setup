# First Expo Router App – Setup Documentation

##  Project Scaffolding Steps

1. Navigated to project directory:`cd prodev-mobile-setup`
2. Initialized the app with Expo Router:`npx create-expo-app@latest`
3. Edited `app/(tabs)/index.tsx` to change the title to:** First App Created**
4. Started the Expo server:`npx expo start`
5. Scanned QR code using Expo Go app on Android
##  Observation After Reset

Ran:`npm run reset-project`

### What happened:
- Cleared build caches
- Cleaned Metro bundler cache
- Removed temp files from `node_modules/.cache`
- Reinitialized app
- Helped solve potential hot-reload or stale asset issues

---

App runs successfully and loads the modified home screen.



