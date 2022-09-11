# Native Android Splash-Screen-in-Flutter

I work on only android splash screen because I am using Windows. I do not have XCode

Splash Screen in Flutter 

How to make a custom splash screen in Flutter?

When the Flutter app launches there is some delay to start the app. During this time Flutter shows a white screen.

That is Launch screen or Splash screen. In this app we shall see how to customize the launch screen.

# For Android

Just navigate to android folder in your project. Now open app then src then main then res then drawable.

- android/app/src/main/res/drawable

- In the drawable folder add the image which you want to show in splash screen.

- Now open launch_background.xml file in the drawable folder.

- Change the color. By default it is white.

- Uncomment the assets lines. There you can add your image.

- If you want to add custom color then add new file in the values folder xyz.xml

- In this file you can add your custom color.

- Also update this color code in the launch_background.xml

- For different resolutions use image of different resolutions in all the mipmap folder generating from App icon website.

# For iOS

- You must have Xcode.

- Open iOS/Runner.xcworkspace

- Open Runner folder and then Assets.xcassets.

- Drag and drop the image of different resolutions.

- To change color open Launchscreen.storyboard file in runner folder.

- runner/Launchscreen.storyboard/view controller scene/View controller/View

- There change the color
