# Installing Git - Mac

## Introduction

These are instructions for installing Git on macOS (formerly known as OS X) operating systems, i.e. Mac computers. If you use a different operating system, locate the appropriate alternative instructions.

## Objectives

You will be able to:

- Check your current Git installation
- Install or update Git as needed

## Checking Your Git Installation

Mac computers come with Git installed by default. If you already have version 2.23 or later installed on your computer, you can skip the rest of the steps in this lesson.

1. Open a terminal window
    - When we ask you to use the terminal, we mean the “Terminal” app in the “Utilities” folder within your “Applications” folder - or, find the "Terminal" app in your Launchpad (often found in a subdirectory named "Other")
2. Type `git --version` and hit Enter
   - It should print out the version of git you are running

If you get a message that says "command not found" when you run this, that means you need to **install** Git. If it prints out a version, you need to look at that version to determine next steps.

The version must be at least 2.23. In other words, this version will work:

```
git version 2.23.1
```

And so will this version:

```
git version 2.34.1
```

But this version will not work and needs to be **upgraded**:

```
git version 2.22.1
```

## Installing or Upgrading Git

If you either don't have Git installed or have an old version, the steps to correct this are essentially the same. You'll install Git and overwrite the old version if needed.

If you are comfortable with the command line and have installed <a href="https://brew.sh/" target="_blank"> homebrew</a>, you should install Git by running the command `brew install git` in a terminal window. If you have no idea what that last sentence meant, please disregard and follow the below steps.

### Overview

Please also reference the image screengrabs for more detail below.

1. Navigate to Git's download page for MacOS <a href="https://git-scm.com/download/mac" target="_blank">here</a>. Since you are not using homebrew, you should click on the latest version number under the Binary Installer option
    - This should take you to another page, where the download of the installer dmg file should begin automatically after a few seconds
2. Double click on the downloaded dmg file to open a small Finder window
3. Double click on the .pkg file to run it, and click "Open" when the pop-up security warning asks if you are sure you want to open it
    - If you get a security warning that simply says the file cannot be opened because it is from an unidentified developer, then:
        - Click on the Apple symbol at the top left of your screen
        - Select “System Preferences” from the drop-down menu
        - Select “Security and Privacy”
        - Select the “General” tag
        - Below the “Allow apps downloaded from” option, click the "Open Anyway" option. You may need to click the lock to make changes, which will prompt you to enter your password
4. When the Installer opens, click "Continue" on each screen, then "Install"
    - You may need to enter your password when prompted
5. When the installation is complete, click the "Close" button
    - If the installation window asks if you want to move the installer .pkg file to trash, you can click “Move to Trash”

### Git Installation Step-by-Step:

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQtsPSXRa47q3beYt81S9lchOz5ZC5vrqK324GH1GuGGQXSALFfpBSF_VWVcm8GrQNqvGfjxZeohx5I/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

### Confirming Your Git Installation

Run the same command as described in the "Checking Your Git Installation" section above, `git --version`. If it is still not returning an appropriate version, try repeating the setup steps or searching for troubleshooting advice online.

## Summary

Congratulations! If you've gotten this far and everything has worked, you have successfully installed Git on your Mac!
