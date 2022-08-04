# flutter_custom_icon

## how to use custom icon in flutter

first of all we have to create flutter app project so in terminal create a flutter app 

1.go to the directory that you want 

2. run flutter create project_name

![basic](https://user-images.githubusercontent.com/85615638/182829325-a76e58f6-683a-4970-ab4a-d5b22d101ea0.PNG)

## Now we want to change + icon in right-down corner to Github icon

### step1: go to [https://www.fluttericon.com/](https://www.fluttericon.com/) and choose and download your selected icons

### step2: when downloaded zip file contain 3 filt .dart .json and in fonts folder .ttf , in fonts folder import font in pabspec.yamel file and copy that .ttf file to root directory in fonts folder

### step3:  copy .dart file to project and import in file where you want to use that downloaded icons 

### step4: now you can use that downloaded icons like this:  Icon(MyFlutterApp.github_circled) instead of  Icon(Icons.add),

![final](https://user-images.githubusercontent.com/85615638/182829348-baa1d008-f018-409c-8cec-a093a6654db7.PNG)



