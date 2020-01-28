To change this app so it will install you will probably need to:
1) Change the applicationId in the gradle build file.
2) Change the android:authorities string to something unique in the provider tag of the Android manifest file.
https://gradlewhy.ghost.io/overcoming-install-failed-conflicting-provider/
