# QR-Quick-Linker
A simple bash script that creates a soft-link to a file, generates and displays a QR code to scan.


Will create a temporary soft-link to the specified file in your webserver's directory, generate a QR code, and display the QR code
to be scanned by a device.  

This script cleans up after itself, deleting the temporary files associated with it, so please do not hard-kill it!

NOTE: Please ensure that you have the proper permissions to access the webserver directory. You may have to use sudo!

## Usage
````qrQuickLink FILE````

## Requirements
- qrencode
- Eye of Mate
- Webserver (Apache, ngix, lighthttp, etc)
- Correct permission level to access webserver directory.

## Installation
There is not much to this script, it is only one file.  
I would recommend copying it to your ````/usr/bin```` folder for easier access on your terminal: ````sudo cp qrQuickLink /usr/bin/````
