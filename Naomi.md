# Sega Naomi

The Sega Naomi is an arcade platform based on the Sega Dreamcast.

## Netbooting

Netbooting is done via a Net Dimm and requires a specific bios version to run.

## Carts

The House Of The Dead 2 originally would only run from a special cart. It originally came in a Naomi with a metal box. It uses an older version of the bios. Recently a special netbootable image of HOTD2 was created which can load in the special version of the BIOS to the Naomi upon boot. This means the game is now playable.

## Ninja Assult

This game only boots from a cart and requires a special Namco I/O. It checks for the name of the IO on boot. The Service/Test buttons on the Naomi will not work on this game.

Ninja Assault uses the screen input part of JVS. For this 0, 0 actually corresponds to the bottom right of the screen, and not the top left as you would normally assume.

## JVS

The Sega Naomi uses the JVS protocol. Interestingly the Sync pin is not required to operate properly for the Naomi to work. The Sync pin can simply be connected to ground and the Naomi will operate with one JVS node.
