# NearChat

BLE nearby chat for Android. Two devices running NearChat advertise a custom BLE service, discover each other, connect, and exchange UTF-8 text messages.

## Build

Open in Android Studio or run GitHub Actions. The workflow builds a debug APK and release AAB and uploads them as the **NearChat-builds** artifact.

## Permissions

Android 12+ requires Bluetooth Scan, Connect, and Advertise permissions. Android 11 and lower uses Fine Location for BLE scanning.
