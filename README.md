# Hello World!

Let's learn cordova

```
sudo npm install -g cordova
npm install -g ios-sim
npm install -g ios-deploy
 
cordova create hello com.example.hello HelloWorld
cd hello
cordova platform add ios
cordova build
cordova emulate ios
cordova run ios

cordova plugin add org.apache.cordova.dialogs
cordova plugin add https://github.com/phonegap-build/PushPlugin
cordova plugin ls
```

## To Read:

- http://docs.phonegap.com/en/3.3.0/guide_cli_index.md.html#The%20Command-Line%20Interface
- http://devgirl.org/2013/07/17/tutorial-implement-push-notifications-in-your-phonegap-application/
- http://docs.phonegap.com/en/3.3.0/cordova_camera_camera.md.html#Camera
