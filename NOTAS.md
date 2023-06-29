# NOTAS

## step by step configuration guide (official documentation)

<https://reactnative.dev/docs/environment-setup>

## If you are having trouble with iOS, try to reinstall the dependencies by running:

* cd ios to navigate to the ios folder.
* bundle install to install Bundler.
* bundle exec pod install to install the iOS dependencies managed by CocoaPods.

## Show availables devices

```cmd
xcrun simctl list devices
```

## Execute using a specific device

```cmd
npx react-native run-ios --simulator="iPhone 8"
```

## Mostrar lista de dispositivos conextados

```cmd
adb devices
```
