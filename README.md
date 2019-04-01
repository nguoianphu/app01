

```
cd $HOME
git clone git@github.com:nguoianphu/cordova-template-framework7-vue-webpack.git
cd cordova-template-framework7-vue-webpack
npm install
npm install -g cordova
```

```
cd $HOME
cordova create app01 com.nguoianphu.app01 App01 --template cordova-template-framework7-vue-webpack
```

```cordova create <project_create_dir> [com.example.projectname] [ProjectClassName] --template cordova-template-framework7-vue-webpack```



```
cordova platforms add android
cordova run browser -- --live-reload
cordova build
```
