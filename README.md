cat428-glitch-text-adventure
============================

A very alpha version of Glitch "running" as an inform7 text adventure for putting onto Playfic.

Turns out that Alakol and current items is _just_ at the maximum limit of the Z-Code virtual machine, we may need to remove
a few streets to make the items more interactive. Let's cross that bridge when we come to it.

Feel free to send me pull requests if you want to add anything. _Maybe_, just _maybe_ one day I'll see if I can get this
set up as a multiplayer Inform7 MUD :)

You can "play" the latest version of the game over at playfic: http://playfic.com/games/revdancatt/text-glitch

*NOTE:* The one file you need to copy over to playfic.com is `text-glitch.inform/Source/story.ni` the rest is just inform7 IDE cruft.


TODO
====

1. Make planting, watering, petting and harvesting of trees and plants work.
2. Make the rocks give rocks (if the player has a pick).
3. Add "money" to the system.
4. Allow the player to sell fruit to the vendor.
5. Allow the user to buy a pick from the vendor.


0.2.5
=====

Finished off all the minimal descriptions for the rooms and added in a bunch of items based on the last snapshot of the world over at the Glitch Encyclopedia. Had to remove several items as it was hitting the memory limit of the Virtual Machine.

0.2.4
=====

Added minimal descriptions to all the streets in Alakol so in theory you can now find your way around the place by just reading the room description.
Also aliased Street to Room just because it feels nicer.

0.2.3
=====

Linked up all the rooms in Alakol


0.2.2
=====

Name all the streets on Alakol, link some of them up.
