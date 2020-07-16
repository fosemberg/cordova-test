## Test your application behavior inside Cordova

Run web application on localhost

Change src of iframe to your application in [index.html](www/index.html)

Install dependencies

```bash
npm install
```

[Install Cordova](https://cordova.apache.org/docs/en/latest/guide/cli/index.html#installing-the-cordova-cli):

```
npm install -g cordova
```

Add a platform

```
cordova platform add android
```

The easiest way to run it - inside Android Studio [full instruction](https://medium.com/@gotoark/how-to-run-cordova-projects-in-android-studio-8f41bdf52be3):
- Open Android Studio  
- Choose File -> New -> Import Project
- Navigate to The CordovaProject’s Directory/platform  
- Select the Folder Android and Press Ok
- After that the Gradle build will begins and let it to be finish.
- Run Project
- Once the Gradle Build finished Click the RUN Icon or shift+F10 to Run the Project
