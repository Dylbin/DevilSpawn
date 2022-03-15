# DevilSpawn



## About

DevilSpawn is a post exploitation multiplexor daemon which is an surveillance tool written in Python. It gives you a command line session with extra functionality between you and a target machine. DevilSpawn gives you the power and convenience of uploading/downloading data, tab completion, taking pictures, location tracking, shell command execution, persistence, escalating privileges, password retrieval, and much more.  This is project is a proof of concept, intended for use on machines you own.

## New In Version 2.0
 - Added support for iOS 12 to 14.8.1
 - Added support for Substitute and libhooker
 - Added partial support for iOS15
 - Now compiled for ARM64E (added support for all 64-bit iOS devices.)
 - More secure socket connection using SSL
 - Linux support
 - Tab completion
 - Improved over all structure and efficiency of session handling
 - Native iOS python support for 64 bit devices


## Getting Started
- Requires python 2.7

### macOS/Linux Installation
```sh
git clone https://github.com/Dylbin/DevilSpawn
cd devilspawn
python devilspawn.py
```

### iOS Installation (Jailbroken)
- Coming soon


### Teensy macOS (USB Injection)
Teensy is a USB development board that can be programmed with the Arduino IDE. It emulates usb keyboard strokes extremely fast and can inject the DevilSpawn payload just in a few seconds.

## Commands

#### iOS
* **alert**          : make alert show up on device
* **battery**        : get battery level
* **bundleids**      : list bundle identifiers
* **cd**             : change directory
* **dhome**          : simulate a double home button press
* **dial**           : dial a phone number
* **download**       : download file
* **getcontacts**    : download addressbook
* **getnotes**       : download notes
* **getpasscode**    : retreive the device passcode
* **getsms**         : download SMS
* **getvol**         : get volume level
* **home**           : simulate a home button press
* **installpro**     : install substrate commands
* **ipod**           : control music player
* **islocked**       : check if the device is locked
* **lastapp**        : get last opened application
* **locate**         : get device location coordinates
* **locationservice**: toggle location services
* **lock**           : simulate a lock button press
* **ls**             : list contents of a directory
* **mic**            : record mic
* **mute**           : update and view mute status
* **open**           : open apps
* **openurl**        : open url on device
* **persistence**    : attempts to re establish connection after close
* **picture**        : take picture through the front or back camera
* **pid**            : get process id
* **respring**       : restart springboard
* **safemode**       : put device into safe mode
* **say**            : text to speach
* **setvol**         : set device volume
* **sysinfo**        : view system information
* **upload**         : upload file
* **vibrate**        : vibrate device


#### Linux
* **cd**             : change directory
* **download**       : download file
* **ls**             : list contents of a directory
* **pid**            : get process id
* **pwd**            : show current directory
* **upload**         : upload file
