## hid-sony
Fake PS4 controllers are not detected properly in Retropie.
For more info check: https://retropie.org.uk/forum/topic/27359/ps4-controller-not-detected-in-retropie-4-6-on-pi-4b

## Build and install
```
$ make && sudo make install
```

## Reload module
```
# rmmod hid_sony && modprobe hid-sony
```