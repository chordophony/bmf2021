# BMF 2021 Edition Overview

### Features
 - Based on Open Source MIDI Controller Software
 - Embedded chip and software supports MIDI via Bluetooth / BLE
 - BLE MIDI supported by iPhone/iPad, Android, Mac, Windows
 - Programmable via Wifi / AP
 - 1 rotary encoder
 - OLED display
 - 2 momentary foot switches
   - Events supported:  press, release, click, double-click, long press
 - 1/4in TRS controller jack 
   - currently supports several external button controllers, notably Digitech FS3X 3-button controller (expression/volume pedal support in the works)
 - Micro-USB for power & firmware updates
 - 3 programmable profiles, each with 20 banks

### "Factory" Built-in Profiles:

#### Default Bank Actions

|Banks|Events|Notes|
|---|---|---|
|A01-A08|each button event sends a different MIDI Control Change number|1/4in=FS3X/Momentary3|
|B09-B16|"... MIDI Program change|1/4in=FS3X/Momentary3|
|C17-C20|MIDI Notes|1/4in=FS3X/Momentary3|

#### Global config for Profiles A & B

|Button|Event|Action|
|---|---|---|
|Right Footswitch|Long Press|Increment Bank + Increment Program Change|
|Right Footswitch|Dbl-Click|Decrement "...|
|Rotary|Jog|Select Bank|
|Rotary|Click|Increment Bank|
|Rotary|Dbl-Click|Decrement Bank|

### Easiest Way to Program

1. Unplug device *recommend keeping micro-usb plugged into device
2. Plug in device then immediately click & hold rotary knob
3. Release when display reads, "Release button for Access Point"
4. From your computer or mobile device, go to Wifi settings and connect to network named "Pedal..."
5. On your device's web browser go to http://bmf-2021-3.local/
6. Use device website to update pedal, bank, and other configurations
7. To return to factory-default Bluetooth only:  repeat steps 1-2,release for Bluetooth

### Tips & Tricks
 - iPhone/iPad - BLE Midi App to connect device https://youtu.be/PRNyZt9T-yk?t=194
 - Examples of apps that support "MIDI learn capability
   - iPhone/iPad - AUM
   - iPhone/iPad - OnSong
   - Mac - Logic Pro, Mainstage, GarageBand,...
   - Mac/Win - Ableton Live,...
   - Many more...
 - ...
