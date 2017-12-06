# GBRE
GB Runtime Environment for iOS

![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Nintendo-Game-Boy-Color-FL.jpg/111px-Nintendo-Game-Boy-Color-FL.jpg)

https://ericgramgb.github.io/GBRE/GBRE.html

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

## How to open ".gb" or ".gbc" file
1. Open "GBRE.html".
2. Tap "Choose File".
3. Browse and select a file.
4. Touch the LCD area of the screen to run.

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

### BTC
`1Dvh3ACuqWnPfUcoUF5fBViaW2T7PEzFGA`

### ETH
`0x878d792217d8188b1818318a00306b3772E9a35b`
