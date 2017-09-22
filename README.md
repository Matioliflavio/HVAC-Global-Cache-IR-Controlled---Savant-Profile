# HVAC-Global-Cache-IR-Controlled---Savant-Profile

Savant Profile to control HVAC system driven by GlobalCache IR devices. This profile can control HVAC over IR directly to savant controller or by IP to send commands to GlobalCache IR based product.
This file can control Midea/Carrier HVAC splits, but you can change IR or GlobalCache code to work with another brands and models.

Fill the profile's serial number with desire port you will send command. For example "1:2" to GlobalCache 2 IR port.  

To change GlobalCache IR command wou must need to copy only bold part to profile

=sendir,1:1*,1,38186,1,1,164,171,17,66,17,24,17,66,17,66,17,24,17,24,17,66,17,24,17,24,17,66,17,24,17,24,17,66,17,66,17,24,17,66,17,66,17,24,17,66,17,66,17,66,17,66,17,66,17,66,17,24,17,66,17,24,17,24,17,24,17,24,17,24,17,24,17,24,17,66,17,66,17,24,17,24,17,24,17,24,17,24,17,66,17,24,17,24,17,66,17,66,17,66,17,66,17,66,17,202,165,171,17,66,17,24,17,66,17,66,17,24,17,24,17,66,17,24,17,24,17,66,17,24,17,24,17,66,17,66,17,24,17,66,17,66,17,24,17,66,17,66,17,66,17,66,17,66,17,66,17,24,17,66,17,24,17,24,17,24,17,24,17,24,17,24,17,24,17,66,17,66,17,24,17,24,17,24,17,24,17,24,17,66,17,24,17,24,17,66,17,66,17,66,17,66,17,66,17,3818*=

