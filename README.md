#eCare - The Monitor device for the elderly
This applcation is designed to support Nursing Aide to **taking care of the elderly.** eCare is using embARC EM Starter Kit with BLE and ad2 pmods. You can observe thorugh our **andorid App** to monitor your **ECG(Electrocardiogram)** or **EMG(Electromyogram)** anywhere.
Let's us begin introduce eCare with you!

* [Introduction](#Introduction)
* [Hardware and Software Setup](#hardware-and-software-setup)
* [User Manual](#user-manual)

## Introduction

- Our project is to provide users to monitor their health by the mobile. 
- We will collect body signal and convert voltage signal to digital signal and then transmit to bluetooth.
- Finally, user can see the EMG and ECG signal from the mobile

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
