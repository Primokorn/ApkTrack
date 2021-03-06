# ApkTrack

ApkTrack is a simple Android application which periodically checks if your installed apps can be updated.

It was created for users who don't use the Google Play Store, but still need to know when new APKs are available for their apps. ApkTrack performs simple website scraping to grab the latest versions of packages present on the device.

This application is distributed under the terms of the [GPL v3 License](https://www.gnu.org/licenses/gpl.html).

-------------------------------

## Usage

![ApkTrack screenshot](http://img4.hostingpics.net/pics/168848apktracksmall.png)

* Click on an application to perform a manual version check.
* The buttons at the top are used to respectively refresh the installed application list and perform a version check for all applications.

That's it!

## Things to keep in mind

* The application will perform HTTP requests both on demand and silently. It does not care whether you are using 3G, 4G or WiFi. Please do not install it if your mobile plan charges data at a premium. 
* Updates, installations and uninstallations are not detected automatically by the application. You have to press the ![](http://img4.hostingpics.net/pics/230860icmenufind.png) button to refresh the installed apps.
* ApkTrack uses regular expressions to scrape webpages, so it may cease to work without notice if the target websites are modified.
* Applications are *not* updated automatically. You still have to find a way to download the latest APKs and sideload them yourself. ApkTrack is simply here to tell you that the update is available.
* Although there is a background service checking for updates every day, it may get killed by the OS. Remember to check for updates manually in the application from time to time.
* ApkTrack has no fancy icon :( Feel free to design one!
* I am by no means an Android developper. This is a project I hacked quickly because I was tired of checking updates manually. If you are learning Android development, what you see in the code should definitely not be considered best practice. You're welcome to point out what I did wrong, though!

-------------------------------

### Download
A precompiled version of the application can be found here: [ApkTrack 1.0](http://kwiatkowski.fr/apktrack/ApkTrack.apk).

### Donations
ApkTrack is completely free, and I don't expect any kind of compensation for using this application. I do like Bitcoins though, so if you want to send some my way, here's an address: ```19wFVDUWhrjRe3rPCsokhcf1w9Stj3Sr6K```
