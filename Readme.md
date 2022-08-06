# Catboxer
![Catbox logo](https://catbox.moe/pictures/logo.png)


Upload files to Catbox (filehost) via Send to right click menu(Windows).

Written in python.

## Installation

Just paste the release file `Catboxer.exe` in the following location:
`C:\Users\YourUserName\AppData\Roaming\Microsoft\Windows\SendTo\`

If you want to upload to your Catbox account:
* Make a new text file `Catboxer.conf` in `C:\Users\YourUserName\AppData\Roaming\Microsoft\Windows\SendTo\`
* Go to https://catbox.moe/user/manage.php
* Copy the userhash and paste it in `Catboxer.conf`

## Usage

* Right click on any file/folder.
* Choose `Send to`.
* Choose `Catboxer.exe`.

The url of the upload will be displayed as well as copied to the clipboard automatically.

## Limitations

Files of sizes above 200MB are not allowed.

## Credits

[Catbox](https://catbox.moe/)

## Building from Source

* Clone this repository
* Run `pip install -r requirements.txt`
* Run `pyinstaller --onefile -i Catboxer.ico Catboxer.py`



