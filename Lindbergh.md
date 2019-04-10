# Sega Lindbergh

The Sega Lindbergh is an arcade platform based off of PC Hardware from the early 2000 period.

## Software

The system runs Monta Vista linux, with the 2.4 and 2.6 linux kernel used for different games. A PCI card known as the _baseboard_ is placed into the system to talk to the controllers over JVS.

Although the system has a CF Card and Hard Disk to play the games, as it is a normal computer it can be set to boot directly from a Hard Disk and so windows/linux could be booted on the Lindbergh with ease.

## Games

- Afterburner Climax
- The House Of The Dead 4
- The House Of The Dead 4 Special
- Let's Go Jungle
- Let's Go Jungle Special
- 2 Step : 2 Spicy
- The House Of The Dead Ex
- Outrun 2 SP
- Sega Race TV
- Initial D 4
- Initial D 5
- Ghost Squad Evolution

## Games

The system initially boots from a CF card which is encrypted with ATA encryption. The CF card runs linux, and starts an application named _segaboot_ which is responsable for checking the system state and running the game.

Games are stored on a Hard Disk Drive in an encrypted format. There are multiple partitions on this drive, that are encrypted with different keys.

When the system starts up, it unencrypts the drive data by mounting it to the linux system, and runs the game from there.

There is a security chip which is used to unencrypt the game, and this is then checked again when the game starts.

The games also check that the soundcard and video card are the correct ones before starting.

## Graphics Card

The following graphics card can be used, and are listed from best to worst.

- NVidia GeForce 7800GS
- NVidia GeForce 7600
- NVidia GeForce 6 Series

Cards have multiple outputs, and multiple games use these.


## Baseboard

The baseboard has a small battery on it to save settings to the EEPROM and flash memory on the card.
