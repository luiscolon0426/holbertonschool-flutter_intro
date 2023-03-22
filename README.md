# Install Flutter Manually (LINUX)

## 1. Make sure you are up to date

Before running any commands, make sure your laptop is up to date:

```
sudo apt update
```

## 2. Install Flutter

You can install Flutter by using the next command:

```
sudo snap install flutter --classic
```

## 3. Display Flutter SDK PATH

One you install the snap, use the following command to display your Flutter SDK path:

```
flutter sdk-path
```

## 3. Check dependencies

Run the following command to see if there are any dependencies you need to install to complete the setup.

```
flutter doctor
```

This command checks your environment and displays a report to the terminal window. The Dart SDK is bundled with Flutter; it is not necessary to install Dart separately. Check the output carefully for other software you might need to install or further tasks to perform.

## DEBUG

if the previous steps dont work, follow this steps:

```
https://linuxhint.com/install-android-studio-linux-mint-and-ubuntu/
```
