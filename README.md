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

<img width="500" alt="image" src="https://user-images.githubusercontent.com/724536/205639993-afba44bd-8d5e-46a7-a7e0-b62e0630f5d8.png">

*Use shortcut*

<img width="500" alt="screen" src="https://user-images.githubusercontent.com/724536/203151489-34c6c22e-79e1-4d65-8c90-ca113ab74bd2.png">


## Git

### Git Worktree

Let's you work in more than a branch at the same time:

**Usage**

`git worktree add ../ios-app-dev dev`

### Git Hook 🚗

- [Swift Format as post commit](https://github.com/phynet/iOS-Tooling/blob/main/post-commit)

let's you run swift Format on staged files after commit, all changes in format will be included in the commit.

- [Name branch hook](https://github.com/phynet/iOS-Tooling/blob/main/name-branch-hook)

Takes the numeric name of the branch and add it into each commit. For example:

    [12345] My feature commit 1 
    [12345] My feature commit 2


## Simulator 🚀

### [SimGenie](https://simgenie.app/) 

Remove all permission without the need to delete the application. Gives you several and important functionalities that allows you to work with the simulator:

- Clean derived data
- Remove all app and SO permission, like push notification
- Push notification payload setup

<img width="500" alt="image" src="https://user-images.githubusercontent.com/724536/206753456-2ff702ea-5267-4d26-af5b-c2a25ab5e43b.png">

### [SimSim](https://github.com/dsmelov/simsim)

Explore application folders while developing for iOS, watchOS or tvOS.

<img width="500" alt="image" src="https://github.com/dsmelov/simsim/raw/master/simsim.png">

### [Control Room](https://github.com/twostraws/ControlRoom)

Control Room is a macOS app that lets you control the simulators for iOS, tvOS, and watchOS – their UI appearance, status bar configuration, and more. It wraps Apple’s own simctl command-line tool, so you’ll need Xcode installed.

- Manipulate System configurations

    <img width="500" alt="imagen" src="https://user-images.githubusercontent.com/22014420/208280417-c0b26406-4dd7-48d1-8102-584faedee2b8.png">

- Manipulate App configurations. In this section, you will find a really useful tool. You could add a push notification payload on the box below, tap `Send Push Notification` and your active simulator is going to receive a push notification 🎉

    <img width="500" alt="imagen" src="https://user-images.githubusercontent.com/22014420/208280738-f69f88fa-f0c1-49f6-a390-87153d6c62f0.png">

- Configure simulator location

    <img width="500" alt="imagen" src="https://user-images.githubusercontent.com/22014420/208280750-265231b1-4627-4148-89f8-3a2795dca7dd.png">


## UI 🎨

- [Sherlock](https://sherlock.inspiredcode.io/)
- [Reveal App](https://revealapp.com/) 
### [Shottr](https://shottr.cc)

Shottr is a small, fast, human-sized screenshot app built for those who care about pixels. It was crafted with Swift, optimized for M1, and is distributed for free.

<img width="700" alt="imagen" src="https://user-images.githubusercontent.com/724536/219422748-a50084ca-06a9-4d4a-bea3-5a47970d6b62.png">

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

### [Raycast](https://www.raycast.com)

Raycast is a blazingly fast, totally extendable launcher. It lets you complete tasks, calculate, share common links, and much more.

<img width="600" alt="image" src="https://user-images.githubusercontent.com/724536/219423918-285b34e2-165f-47ac-b25b-201ae36a3d3a.png">

