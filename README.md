# Clip Snap Paint
This is a snap of [Clip Studio paint](https://www.clipstudio.net/) for Linux.
It packages CSP `v1.9.11`, wine 6 staging and the required changes to launch the application in a linux distribution.

It has been packaged using [sommelier-core](https://github.com/snapcrafters/sommelier-core)

# Motivation behind this project
One of my biggest hurdles when transitioning from a Windows system to a Linux distribution on my daily driver was maintaing use of my favorite applications. I managed to set up a Wine configuration that let me keep using CSP on my linux machine well enough to keep working, even with some flaws, and kept me content for a couple of years.

Now, I see more artists considering making the switch sharing my same concern, so I hope this project will make that step easier!

# Installation
- Download a release from the releases page.
- Install it in your computer with

```
snap install ${clip-snap-paint}.snap --dangerous
```

- Run `clip-snap-paint` from the command line or launch ClipStudioPaint from your application list
- Follow the steps for installation making sure *not to change the installation path* in the Clip Studio installer.

## Activating the license
You will need a valid Clip Studio license in order to use all of CSP's features.
Online features for this snap do not work correctly, such as log-in for license activation.

In order to activate your installation, you will need to perform an offline activation.
- Select "I already have a license"

![image](https://user-images.githubusercontent.com/80431234/155963784-f3381498-ee28-496a-a522-1dd809e7084e.png)

- "Click here if your device is not connected to the internet"
  - If this option does not show, close the program, disconnect from the internet and try again

![image](https://user-images.githubusercontent.com/80431234/155964258-8a4b1f95-2f65-4a43-816c-72fcfc8edaab.png)

- Continue with the steps provided in the program

# Contributing
This project is open to any contributions or issues that may arise.
[Submit a new issue](https://github.com/mpRegalado/clip-snap-paint/issues/new) - [Create a pull request](https://github.com/mpRegalado/clip-snap-paint/compare)

# License
This snap manifest is released under MIT license. ClipStudioPaint is a proprietary application owned by [CELSYS](https://www.clipstudio.net)
