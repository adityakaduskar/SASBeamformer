# SASBeamformer
SAS Beamforming assignment for my course EEE598 - Remote Sensing and Synthetic Aperture Imaging
## Requirements
"measurements.py"  
◦Contains raw AirSAS measurements with shape (number of measurements, number of samples).  
  
"pixels.npy"  
◦Image pixels coordinates with shape (22500, 3) corresponding to a (150, 150) sized image.  
  
"tx_coords.npy"  
◦Speaker coordinates with shape (360, 3) corresponding to 360 transmitter locations.   
  
"rx_coords.npy"  
◦Microphone coordinates with shape (360, 3) corresponding to 360 reciever locations.This array is aligned with tx_coords.npy.  
  
"transmit_wfm.npy"  
◦The 100 sample transmit LFM waveform with shape (100). The waveform is .001 (s) duration LFM from 30 kHz→ 10 kHz. 
