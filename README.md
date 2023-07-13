# Installation
These are the iTerm2 setup I used for Mac Air 13.6" M2 Chip

## iTerm

iTerm is a popular terminal emulator for macOS that provides an enhanced and customizable command-line interface. Here are the reasons why I prefer to use it rather than terminal:
1. Features & Customization : I can customize colors, fonts, window transparency, and configure settings to match preferences. Split panes, tabs, search functionality, autocomplete, and also key mappings.
2. User Interface : iTerm has a more modern and visually appealing user interfaace compared to the default Terminal application.

Is using iTerm as a replacement for the macOS Terminal app safe?

You can read it in the following link:

[https://www.malwarebytes.com/blog/news/2021/09/new-mac-malware-masquerades-as-iterm2-remote-desktop-and-other-apps]

### Install Homebrew

Homebrew is a popular package manager for macOS.
With Homebrew, users can easily install, update, and uninstall software packages directly from the command line. 
It allows users to easily access and install software that may not be readily available through the official macOS App store. 

**Installing apps from Homebrew is generally considered safe although we have to keep in mind that no software ecosystem is entirely immune to potential vulnerabilities.** 

`homebrew install`
Open `Terminal` on Mac (Spotlight shortcut F4) 

Paste the following command and press return

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
The command will initiate the installation process by downloading the Homebrew installation script and starting the installation. 

If you are asked for an administrator password, type your password. 

You can check it by typing the following in your terminal. This command will check if Homebrew is installed correctly and detects any potential issues. 

```
brew doctor
```
Check brew version 

```
brew --version
```
### Install iTerm

In the Terminal, run the following command to install iTerm:

```
brew install --cask iterm2
```

Homebrew will download the iTerm package and its dependencies. This may take a few minutes.

Once it is complete, you can launch it from Spotlight ( which is easier)

Installing iTerm through Homebrew allows you to benefit from Homebrew's package management system which makes it easier to update and manage iTerm alongside other installed packages on your system. 

***The `--cask` option is used with Homebrew to install macOS applications.***

To check iTerm is installed properly, you can type the following command in Terminal
```
open -a iTerm
```
This command attempts to open iTerm and if installed correctly, it will launch the application. 



