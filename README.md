# Welcome to the Real Time FM SDRadio

This repository contains the final year MEng project of Themba Kaonga.

It revolves around an application designed in MATLAB code which:

- Demodulates FM complex baseband data from an SDR
- Plays FM audio output to PC audio device
- Calculates & displays the channel SNR depending on SNR bandwidth range
- Uses SNR to estimate amount of in band FM stations 
- Can automatically sweep over the entire FM band to search for stations (88.5MHz-107.0MHz)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

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



