# Gore-Particles (WIP)
GZDoom mini mod that adds fancy blood particles animations

Mod uses sound effects from loaded gore mods, but you can also use
[this sfx add-on](https://drive.google.com/file/d/1m2uRR5Aw2YcJhw8IR-lAHvpnnfMVo0fB/view?usp=sharing)

## Features

* Various volumetric blood effects based on GZDoom particles
* Bleeding wounds
* Built in blood colours for vanilla monsters (like green blood for hell knight or blue for cacodemon)
* Customizable blood colour
* Compatibility with other gameplay, monsters or gore mods
#

Because most of the blood effects are only made of particles (excluding blood streams), mod dosen't create any new actors and won't affect performance much.

But because all of the blood is visualized with particles, I highly recommend use other mods in case you want blood puddles and spots.

(GZDoom particles aren't working in such a way that when their amount hit the limit, and new particle need to spawn, old ones will wanish, instead, new particles won't spawn until one of the old ones won't disappear)

## TO DO

* Add effect for squishing
* Rework gibing calculation (make something similar to UGibs)
* Textured particles for wound blood (not sure about this one)
* Utilization of sounds from loaded gore mods (similar to what was done in the cleaning mod)
* Wounds pitch on dead bodies from their initial position
* Change vanilla monsters blood color on sapwn
* Hideous Destructor compatibility
* Blood amount and size based on damage
* Wounds size based on damage
* Configurable blood brightness and transparancy
* Partially invisible blood
* Running clarify line in options menu (like in Nashgore)
