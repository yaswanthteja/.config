
# MY  Powershell Setup! 👋

First download latest Powershell and windows terminal  from microsoft store

## Pre-Requirments
- [Nerdfonts](https://github.com/ryanoasis/nerd-fonts/releases) -  My personal choice (hack font)
Download  hack.zip and extract the zip file and install the fonts. consists like this(hack of Nerd Complete mono windows  compatable (opentype)

# Install scoop to powershell
 - [scoop](https://scoop.sh/) - A command-line installer , type the following commands in powershell

```bash
 iwr -useb get.scoop.sh | iex

 scoop install curl sudo jq
 ```


# Install Git from powershell

 - [Git for windows](https://gitforwindows.org/) just type the following command in powershell.
```bash 
 winget install -e --id Git.Git
```
It will install git to windows


# Install neovim  to powershell
```bash
  scoop install neovim gcc
```
- Next  create a user profile 

- You  can do this in two methods
@@@@@@@@@@@@@@@@1 Simple method @@@@@@@@@@@@@@@

1.Download [.config](https://github.com/yaswanthteja/.config) folder and move this folder  to ( C:\Users\your username\) 
 if you want to find user name just press windows+R or open run and type this 'netplwiz' then it will show  it will show your   username.
 (or)  
- In 'C drive' you will have users folder and in that you will find your usernamefolder(it will be your system name ) so paste these files over there.
Note:
in the .config folder there will be two files
# 1. user_profile.ps1
 # 2. yeswa.omp.json 

here you need to rename the  ' 2nd  file name 'to yourusername.omp.json   

(eg: yeswa.omp.json) here yeswa is my username, so replace or rename yeswa to your username.
if your username is tuf change to tuf.omp.json)

if you use the above method , in powershell you need to use the following command


```bash
 cd .config/powershell
```
And Continue this Process 
- If you uses the above 1st  method skip the 2nd method to avoid errors


-@@@@@@@@@@@@@@@@@@@@@@@@ 2 method @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
- ### 2.ManualProcess

 ######skip the following steps from here#######
------------------------------------------------------------------------
```bash
 mkdir .config/powershell/user_profile.ps1
```
  - It will create a folder in 'Cdrive' as .config

   - And inside of it  will create a powershell folder 

   - And inside of it will create this file user_profile.ps1 
   now type this command
```bash
   nvim user_profile.ps1
```
to insert the text just press i button in keyboard  and paste the text

and to save the text press ESC  button  in keyboard and  press :wq  buttons and  hit enter button

if you face any error press ESC button and :q! buttons  and enterbutton  this will not save any text in the file
so you need  to follow the first method.


   Now u need to copy the text from [user_profile.ps1](https://github.com/yaswanthteja/.config/blob/main/powershell/user_profile.ps1) and paste  the text  into the file

  In the same way you need to create another file and paste the text into it

######################### skip upto here#########################################
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@




# Install oh My Posh to powershell

 - [Oh My Posh](https://ohmyposh.dev/) -Prompt theme engine
 For installing oh my posh  type the following commands in powershell
 ```bash
 Install -Module posh-git -Scope CurrentUser -Force  

 Install -Module oh-my-posh -Scope CurrentUser -Force
 ```
  # Install nvm  in power shell
 ```bash 
 scoop install nvm

 ```
 
 # Install Terminal Icons in powershell
- [Terminal Icons](https://github.com/devblackops/Terminal-Icons) - Folder and file icons
To install
 ```bash
 Install-Module -Name Terminal-Icons -Repository PSGallery -Force

Import-Module Terminal-Icons
```
# Install Z in powershell

- [Z](https://www.powershellgallery.com/packages/z/1.1.13)  - Directory jumper
```bash
Install-Module -Name z -Force

zdesk
```
# Install PSR ReadLine in powershell
[PSR ReadLine](https://docs.microsoft.com/en-us/powershell/module/psreadline/?view=powershell-7.2)  - Cmdlets for customizing the editing environment, used for autocompletion
```bash
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck

set-PSReadLineOption -PredictionSource History

set-PSReadLineOption -PredictionViewStyle ListView
```
# Install PSFzf in powershell

- [PSFzf](https://github.com/kelleyma49/PSFzf) - Fuzzy finder
```bash
Install-Module -Name PSFzf -Scope CurrentUser -Force

Set-PSFzfOption -PSReadLineChordProvider 'Ctrl+f' -PSReadLineChordReverseHistory 'Ctrl+r'
```

# you can set themes 

[Themes](https://ohmyposh.dev/docs/themes) ftom the themes youcan get any theme for free

```bash
Set-PoshPrompt -slim
```
set-PoshPrompt - theme name and hit enter
## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform

