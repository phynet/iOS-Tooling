# iOS Tooling and Workflows
The purpose of this repo is to share knowledge about the tooling that you usually use while developing iOS applications. Those can vary from scripts, to apps, workflows, to any other form of tool that you find helpful to share with the community.

You are welcomed to add tools, scripts or any other app that you use and is worth to share with the comunity. 🦾


## Xcode Install ⚙️

- [XCversion](https://github.com/xcpretty/xcode-install)
- [Xcodes (GUI)](https://github.com/RobotsAndPencils/xcodes) 

## Proxy 💻

- [Proxyman](https://proxyman.io/)


## Deeplink and Universal link shortcut  🙌

- [Automator script](https://github.com/phynet/iOS-Tooling/blob/main/open%20in%20simulator.zip)

The script let's you open a DL or UL using a string text with a keyboard shortcut. Just highligth them as if you were to copy or paste it and use the keyboard shortcut that you setup before.
The example app is from just eat, thanks to them for open source an app that has deeplinks: 

*Setup Keyboard shortcut*

<img width="507" alt="image" src="https://user-images.githubusercontent.com/724536/205639993-afba44bd-8d5e-46a7-a7e0-b62e0630f5d8.png">

*Use shortcut*

<img width="422" alt="screen" src="https://user-images.githubusercontent.com/724536/203151489-34c6c22e-79e1-4d65-8c90-ca113ab74bd2.png">

## Git Hook 🚗

- [Swift Format](https://github.com/phynet/iOS-Tooling/blob/main/post-commit)
- [Name branch hook](https://github.com/phynet/iOS-Tooling/blob/main/name-branch-hook)


## Simulator 🚀

- [SimGenie](https://simgenie.app/) 

## UI. 🎨

- [Sherlock](https://sherlock.inspiredcode.io/)
- [Reveal App](https://revealapp.com/) 

## Shortcuts 🎺

- [Delete derived data with a default name](https://github.com/phynet/iOS-Tooling/blob/main/shortcuts/Derived_Data_default_project.shortcut) (mine, just remove the name and add your app's name)
- [Delete derived data completely](https://github.com/phynet/iOS-Tooling/blob/main/shortcuts/Derived_Data_default_project.shortcut)

## Command Line Tools 🛠

### Image Manipulation
Sometimes you need to combine several screenshots from your ongoing work to easily ask details from QA or your PM. `convert` [command line tool](https://legacy.imagemagick.org/script/convert.php) can be used to merge several images into one, crop, and resize images.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/22014420/206066590-0c2d4ac7-cf76-42d0-805c-b0beedfd440b.png">

#### Installation:
```
brew install imagemagick
```
#### Usage:
* To create a horizontal image:
```
convert image_1_name.png image_2_name.png image_n_name.png +append output_name.png
```
* To create a vertical image:
```
convert image_1_name.png image_2_name.png image_n_name.png -append output_name.png
```
