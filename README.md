# penguinshroom
This is an extremely experimental Python script for making WINEPREFIXes for GOG Spore + ModAPI.

***This documentation is not complete!***
## Requirements
- Python 3 (modules are included such as `requests` and `colorama` which have to be installed using pip)
- Wine (reccomended 6.0+)
- Internet access (to GitHub specifically)
- A keyboard and a brain

*This script was designed and tested on Arch Linux 64-bit. Your mileage may vary. I haven't tested this on MacOS or Windows, but it probably doesn't work*

## Setup
This script requires that you have the backup installers for Spore provided by GOG.com. They need to be in the same folder as the script.
The backup installers and their components need to be renamed.
- The .exe file should be named "Installer.exe" *exactly*
- The 4GB .bin file should be named "Setup1.bin" *exactly*
- The 400MB .bin file should be named "Setup2.bin" *exactly*
If the script cannot find these files, it will not run.
### Why?
I don't know if GOG will change the names of these installers. If you find a better solution, please let me know.


Your folder should look like this:

![image](https://user-images.githubusercontent.com/76428041/233824601-89cd8d5b-bc31-47f0-9890-49779b29ce29.png)

Now, run the script in your terminal in the same directory as the one you dumped the installers and script into. The command will probably look like this:
```
python3 main.py
```
