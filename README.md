# PlayHeroSoundTick
 
This tool is used to modify xml files in a specified directory. It is particularly useful for changing the value of eventName attribute for elements with the tag Event and attribute eventName='PlayHeroSoundTick'.

## Requirements

* python version 3.x
* os
* datetime
* xml.etree.ElementTree as ET

## Feature

* Appends "_Skin(Enter skin number)" to the value of the "value" attribute

## How to use

### Windows

* Run the script `PlayHeroSoundTick.py` or Download [PlayHeroSoundTick.exe](https://github.com/xxviiixmmiv/PlayHeroSoundTick/releases/download/stable-releases/PlayHeroSoundTick.exe)
* Enter the directory path where the xml files are located.
* Enter the desired skin number.

## Preview

![image](https://cdn.discordapp.com/attachments/1064379069313060864/1064387676603691028/playherosoundtick.png)

## Note

* Be careful and make sure to backup your files before running the script.
* If the script encounters any errors, it will not modify those files and will continue to the next file.
* script will not change the files in directory if ET.ParseError occurs.
* If folder or file address not found, script will notify user and exit.

## Contact

For any issues or support please contact the developer on Github: https://github.com/xxviiixmmiv

## License

(c) Curelight. All rights reserved.

## Version
10.0.19044.2486 (Stable)