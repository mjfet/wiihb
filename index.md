# Wii Homebrew Guide
##### By [@mjfet](https://github.com/mjfet)
##### Join WiiTech @ [https://discord.gg/kj74FMASJH](https://discord.gg/kj74FMASJH)


### Requirements
- A computer (a phone might work, but probably not an iPhone)
- A Wii on System Menu 4.3U/J/E/K With Internet Access (Wii Mini/vWii will be in a different tutorial)
- SD Card (2GB+FAT32)
- SD Card Reader


## Before wii start (See what I did there!)
Check, is your SD Card reader functioning, and your SD Card formatted to FAT32. To check, right click on your drive and click properties. If not, [Click Here](fat32).


## Getting the files together.

Today the exploit I am using is Letterbomb, which is an exploit using the message board. 
Go to https://please.hackmii.com/ and input your MAC Address and correct version or it wont show/your Wii will freeze. If this does happen, retry it.
Once you have put all the details in extract the zip and extract it onto your SD.

## It's Wii Time

Insert the SD into your Wii, and open the message board. It should look like this:
![bomb](https://github.com/mjfet/wiihb/blob/main/bombbomb.png?raw=true)
If it doesn't show, check the dates around it (e.g. if its the 6/9, check the 5/9 and 7/9). Open the letter

## The Fun Part

Your wii should go black then start spitting out some text, if you see this, you did it. 
![dont get scammed](https://github.com/mjfet/wiihb/blob/main/ScamScreen.png?raw=true)
When it loads, press 1, and enter the HackMii installer.

## Installing the Homebrew Channel
When you get to this screen, you cannot use your pointer, so you have to use the D-Pad. Select Install Homebrew Channel.
![hbchannelinstall](https://github.com/mjfet/wiihb/blob/main/HBCHANNEL.png?raw=true)
When finished, press continue. Then go to BootMii, and install as IOS.

## Optional: BootMii as Boot2

When installing BootMii, some Wiis (the early models) support BootMii as boot2 (aka on startup) to create an unbrickable wii, If you can, install as IOS and boot2. Select exit to enter the Homebrew Channel


## Enter the world of Homebrew Apps
Here is an example app structure
`💾 SD Card:`
<br>
`┣ 📂 apps`
<br>
`┃ ┣ 📂Priiloader`
<br>
`┃ ┃ ┣  boot.dol / boot.elf`
<br>
`┃ ┃ ┣  icon.png`
<br>
`┃ ┃ ┗  meta.xml`
<br>
`┃ ┗ 📂BounceWii`
<br>
`┃ ┃ ┣  boot.dol / boot.elf`
<br>
`┃ ┃ ┣  icon.png`
<br>
`┃ ┃ ┗  meta.xml`
<br>
The first thing we will install is [Priiloader](https://hbb1.oscwii.org/hbb/priiloader/priiloader.zip). Click the link and extract the folder inside `apps` inside the zip, to the `apps` folder on your SD Card. Put the SD card in your wii, and open the Homebrew Channel. Priiloader Installer should be there. Open the app and install Priiloader.

## The end.
Tips for further on:

- Use the same tutorial for extracting Priiloader to install other apps, like [BounceWii](https://oscwii.org/library/app/BounceWii)! A great place for homebrew apps is [WiiBrew](wiibrew.org) or [OSC](https://oscwii.org).
- Joining the WiiTech Discord!
<br>
Goodbye!
