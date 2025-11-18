# Gore-Particles (WIP)
GZDoom mini mod that adds fancy blood particles animations

Mod uses sound effects from loaded gore mods, but you can also use
[this sfx add-on](https://drive.google.com/file/d/1m2uRR5Aw2YcJhw8IR-lAHvpnnfMVo0fB/view?usp=sharing)

## Features

* Various volumetric blood effects based on GZDoom particles
* High customization level:
    * You can choose which effects will or will not appear
    * Configurable size, speed and particles amount of the effects
    * Configurable color, brightness and trasparancy of the blood
* Bleeding wounds
* Built in blood colours for vanilla monsters (like green blood for hell knight or blue for cacodemon)
* Compatibility with other gameplay, monsters or gore mods
* Client-side:
   Most of the mod's options are only affecting one player's game, and even more, it won't cause desync if only one of the players will has the mod loaded, till all of the server options are turned off (server options are marked with the "🌐" symbol)
#

There is no actors in the mod, which lowers its impact on the performance and makes most of the options client side

__Mod requires GZDoom 4.14.2 or newer__

## Credits

Mod utilizes [LibToolTip](https://github.com/ToxicFrog/doom-mods/tree/main/libtooltipmenu) by ToxicFrog

## TO DO

* Rework gibbing calculation (make something similar to UGibs)
* Textured particles for wound blood (not sure about this one)
* Blood amount and size based on damage
* Wounds size based on damage
* Add performance settings pressets
* Work on projectiles impcat
