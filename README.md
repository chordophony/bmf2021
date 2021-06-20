# BMF 2021 Edition Overview
https://reverb.com/item/40525980-bluetooth-midi-footpedal

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

### Quick Start

#### Step 1: Plug it in
[Watch how|https://github.com/chordophony/bmf2021/blob/main/videos/BMF2021%20::%20Step%201%20-%20Plug%20it%20in.mov]

#### Step 2: Connect to device
https://github.com/chordophony/bmf2021/blob/main/videos/BMF2021%20::%20Step%202%20-%20Connect%20to%20device%20from%20iPhone%20or%20iPad.mov
https://github.com/chordophony/bmf2021/blob/main/videos/BMF2021%20::%20Step%202%20-%20Or%20connect%20to%20device%20from%20Mac%20(or%20Windows%20or%20Android).mov

#### Step 3: Set up your apps (this is a one time step)
https://github.com/chordophony/bmf2021/blob/main/videos/BMF2021%20::%20Step%203%20-%20set%20up%20your%20apps.mov

#### Step 4: Play

### User Guide
#### Connecting the device
1. Download BLE Midi App or AUM in the App Store - both of these apps allow connections to BLE Midi devices
   - BLE Midi App (free):  https://apps.apple.com/us/app/bluetooth-midi-connect/id1108321791
   - AUM ($20, but this is a terrific iPhone/iPad music production app):  https://apps.apple.com/us/app/aum-audio-mixer/id1055636344
2. Plug in the BMF2021 device using micro-usb port on the right side of device
   - Use any USB power supply, e.g. a battery USB charger or a wall plug USB charger
3. Open BLE Midi App, and connect as seen in this video
4. You now have a Bluetooth MIDI connection established between the BMF2021 and the iPhone/iPad

#### How I use BMF2021
##### Changing patches of plugins in AUM on iPad/iPhond, Muting Channels, Toggle Record
 - App link:  https://apps.apple.com/us/app/aum-audio-mixer/id1055636344
##### Using it as a Loop Pedal with Group the Loop app on iPad/iPhone
 - Video:
 - App link:  https://apps.apple.com/us/app/group-the-loop/id1029416579
##### Page-turning and song-switching in OnSong app on iPad/iPhone
 - Video:
 - App link:  https://apps.apple.com/us/app/onsong-pro/id502344938

### How to Use BMF2021 with Mac
1. Open the Audio Midi Setup app (built-in:  /Applications/Utilities/Audio Midi Setup)
2. Window menu -> Show MIDI Studio
3. Click on the bluetooth icon in menu bar
4. Find the BMF2021 device in the list (it will be an 8 digit "0-9,A-F" code)
5. Click Connect

### Other ways you could use BMF2021
#### Updating controls in Apple's MainStage app on Mac
 - https://support.apple.com/guide/mainstage/learn-a-controller-assignment-mstg338d4728/3.5/mac/11.3.1
#### Automating apps like Logic Pro
 - https://support.apple.com/lv-lv/guide/logicpro/lgcp0155c51f/mac
#### Automating music production apps like Ableton Live
 - https://help.ableton.com/hc/en-us/articles/209774265-How-to-use-a-hardware-synthesizer-with-Live#furtheroptions

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

1. Unplug / turn off power source for device
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
