# Welcome to the Real Time FM SDRadio

This repository contains the final year MEng project of Themba Kaonga.

It revolves around an application designed in MATLAB code which:

- Demodulates FM complex baseband data from an SDR
- Plays FM audio output to PC audio device
- Calculates & displays the channel SNR depending on SNR bandwidth range
- Uses SNR to estimate amount of in band FM stations 
- Can automatically sweep over the entire FM band to search for stations (88.5MHz-107.0MHz)

## Getting Started

### To use the application:
- Start MATLAB on your machine
- Double click on the "Real_Time_FM_Demod.mlapp" file in the 'Current Folder' window
- The app window will popup, after which simulation parameters can be selected and run by clicking the interactive buttons

### To view or edit the application design and/or functionality:
- Start MATLAB on your machine
- Open the App Designer client in MATLAB by typing "appdesigner" to the command window
- In App Designer, open the "Real_Time_FM_Demod.mlapp" file by double clicking on it
- Access the source code by clicking on the "Code View" tab
- Access the application's UI design by clicking on the "Design View" tab.
- To execute the application after changes have been made, click the "Run" button in App Designer 

### To use the Simulink model:
- Start MATLAB on your machine
- Double click on the "fm_demod.slx" file in the 'Current Folder' window
- Click on the "Run" button to start model simulation

## Prerequisites

To use the RT FM SDRadio, the tools needed are:

## MATLAB R2018a or newer
- DSP Toolbox
- Communications Toolbox
- RTL-SDR Support from Communications Toolbox
- Simulink

## RTL-SDR hardware (any device with RTL2832U chip)
Includes:
- Generic RTL2832U (e.g. hama nano)
- ezcap USB 2.0 DVB-T/DAB/FM dongle
- NooElec SDR family of devices
- Other devices listed at https://osmocom.org/projects/rtl-sdr/wiki/Rtl-sdr#SupportedHardware

# Further Improvements

- Adding support for the Ettus USRP devices (B200, X300 and N200 series & E310 device)



