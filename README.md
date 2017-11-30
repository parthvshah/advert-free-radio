# advert-free-radio
This program can be used to listen to internet or conventional radio advert free. It overlays the adverts with songs from your library or songs similar to what were playing. In this version, the overlay needs fixing.

# WIP
This program is still under developement.
Future updates include:
- Switching from ACR-Cloud for the fingerprinting by building our own library of adverts for a particular region
- Live overlays for truly advert free streaming of radio
- Developing an application of sorts to enable use of this program
- Physical 'switch' button to ensure an advert is always skipped

## Installation
Currently supported on Windows 10 only. 

Download and install the following dependencies:
- [acrcloud](https://github.com/acrcloud/acrcloud_sdk_python)
- [pygn](https://github.com/cweichen/pygn)
- [mp3splt](http://mp3splt.sourceforge.net/mp3splt_page/downloads.php)
- [youtube-dl](https://rg3.github.io/youtube-dl/)

## Instructions 
Run 'mainBranch.py' after editing the input file name. This file can be a recording of the radio. Play the out.mp3 file to listen to the entire clip advert free.
