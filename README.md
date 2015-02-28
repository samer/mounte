A tiny wrapper around hdiutil that helps you mount an encrypted image on OS X.
I made this because OS X does not allow you to paste passwords into "secure" text boxes, like the one you get when you double click on an encrypted image. 
This is annoying if you are using a password manager. 

This script also clears your clipboard after mounting the disk, and opens the mounted image in Finder.

## Installation
Copy `mounte` to`/usr/local/bin` or anywhere else in your `$PATH`.

## Usage
`mounte /path/to/image`

## License
MIT
