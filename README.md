## Convert ReactJs website into an Android App using [Capacitor.js](https://capacitorjs.com/)

* Firstly create an react app using:
```npx create-react-app appname```
* Then install capacitor.js by writing: ```npm install @capacitor/cli @capacitor/core```
* After installing capacitor.js use the following command: ```npx cap init```
  * This will ask Appname and Appid
* After initilizing capacitor.js a file named ```capacitor.config.json``` will be added into your root folder looks something like this:
  * ![image](https://user-images.githubusercontent.com/57860123/114307400-0f5ba600-9afd-11eb-89af-e9f6430e869f.png)\
  * you need to change __webDir__ from 'www' to 'build' as shown\
  * ![image](https://user-images.githubusercontent.com/57860123/114307435-34e8af80-9afd-11eb-9fe2-cce6cf227f09.png)
* Then run ```npm run build``` to make build of your app.
* Then write ```npx cap add android``` to make you app for android or write ```npx cap add ios``` to make yor app for ios.
* Then write ```npx cap open android``` to open it on android studio. Make sure that Android Studio is installed on your system.
* Make apk using Android Studio and your react app is ready to use😊.
