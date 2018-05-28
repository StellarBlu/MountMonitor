# MountMonitor
MountMonitor is an Arduino Nano based monitoring device for a German Equatorial Mount (GEM) used for astrophotography.

The device is attached to the counterweight bar of the GEM, and uses a 3-axis accelerometer to monitor the position of the RA axis of the mount.

The device is calibrated by pressing a momentary action switch while the mount is in the park position, and again at the meridian limit. 

It drives relays to indicate when the RA axis is in the home position and when the mount is at the meridian limit.

A second MountMonitor can be attached to the declination axis of the mount to show when the declination axis is in the home position. 
