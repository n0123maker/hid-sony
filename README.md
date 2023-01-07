## hid-sony
Fake PS4 controllers connected with USB cable are not detected properly in Retropie.  
For more info check: https://retropie.org.uk/forum/topic/27359/ps4-controller-not-detected-in-retropie-4-6-on-pi-4b

## Instructions
In EmulationStation press F4 to enter the shell.
```
$ git clone https://github.com/n0123maker/hid-sony
$ cd hid-sony
$ make && sudo make install
$ sudo rmmod hid_sony
$ sudo modprobe hid-sony
```
Now the controller should be connected properly.  
Restart EmulationStation.
```
$ emulationstation
```