# GBRE
GB Runtime Environment for iOS https://ericgram.github.io/GBRE/GBRE.html

## Browsers
work well
* iOS Safari
* Google Chrome

not
* Firefox (due to AudioBuffer handling)
* IE (no audio support)

## Cartridge Type
supported
* DMG (MBC1, MBC2, MBC3, MBC5, MBC7)

also
* CGB (CPU double speed mode, RAM bank, VRAM bank, color palette, new DMA, accelerometer)

## Keyboard
* W - Up / A - Left / S - Down / D - Right
* L - A / K - B / I - Start / O - Select

## How to open "your_own_rom.gb" on iOS devices
...using Dropbox

1. Upload "GBRE.html" and "your_own_rom.gb" to Dropbox.
2. Open your account page in iOS Safari.
3. Get a link to the ROM file. (Its URL should start with "https ://dl-web.dropbox.com".)
4. Open "GBRE.html".
5. Tap "Open URL".
6. Paste a link.
7. Run. (It is recommended to close all tabs and reopen it.)

(If you upload a file to the web server that is configured to send "Access-Control-Allow-Origin" header, you can specify the URL directly.)

## Notes of some features
* "Save" - Write save data to localStorage and base64 encoded text to textarea. (Save command should be done after saving in game.)
* "Load" - Read save data from localStorage. (Load command should be done during startup.)
* "Load Text" - Read save data from base64 encoded text in textarea.
* "30 fps" - Frame skip.
* "60 fps" - Normal.
* "120 fps" - More accurate audio timing.
* "999 fps" - No wait.
* "Controller" - Adjust controller size.
* "2P" - Boot a second GB to communicate or exchange data.
