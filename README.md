## Introduction

- Our project is to provide users to monitor their health by the mobile. 
- We will collect body signal and convert voltage signal to digital signal and then transmit to bluetooth.
- Finally, user can see the EMG and ECG signal from the mobile
- [ demo vedio ][1]

## HW/SW Setup

* Required Hardware
  - embARC board
  - ble module
  - Pmod adc module
  - smartphone(andorid system)
  - Analog Front End(AFE)

* Required Software
  - ARC GNU toolset
  - Serial port terminal such as putty, tera-trem
  - ExG android app

## User manual

### Before run this application

- Download source code from github, and install app into your smartphone

### Run this application

- Compile the source code in the arc_gnu toolset
- Download the code into your EMSK Board. Be sure the switch 1 and 2 is off state
- Turn on the ExG andorid app on your smartphone
- Choose the ble UUID in the app list
- Finally, place the sensor on your body and you can see the signal on the mobile 

[1]:http://v.youku.com/v_show/id_XMzYzOTc3NDMzNg==.html?spm=a2h3j.8428770.3416059.1 "demo vedio"
