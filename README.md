# ffmpeg-updater
An Python script that checks for ffmpeg updates from https://ffmpeg.zeranoe.com/builds/ and install them

~In order for the script to work correctly you need to put it in the same folder as the ffmpeg folder that should to have the name "ffmpeg" and also you need to create a file in ffmpeg folder with the name of the ffmpeg version~

Or you can just start the script in a empty folder and it will do that for you.

**Example** : 

main.py

ffmpeg ↓
* bin
* doc
* presets
* ffmpeg-20180820-78d4b6b-win64-static
* LICENSE.txt
* README.txt

## Requirements ##
* bs4 (pip install beautifulsoup4)
* html5lib (pip install html5lib)

Tested on Windows 7 64bit, Windows 10 64bit
