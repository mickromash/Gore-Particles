# Gore-Particles (WIP)
GZDoom mini mod that adds fancy blood particles animations

## Features

* Various blood effects based on GZDoom particles
* Bleeding wounds
* Built in blood colours for vanilla monsters (like green blood for hell knight or blue for cacodemon)
* Customizable blood colour
* Compatibility with other gameplay, monsters or gore mods
#

Because most of the blood effects are only made of particles (excluding blood streams and bleeding wounds), mod dosen't create any new actors and has pretty much no effect on the performance.

But because all of the blood is visualized with particles, I highly recommend use other mods in case you want blood puddles and spots.

(GZDoom particles aren't working in such a way that when their amount hit the limit, and new particle need to spawn, old ones will wanish, instead, new particles won't spawn until one of the old ones won't disappear)

## TO DO

* Add blood mist for gibbing
* Add more effects for gibbing
* Add effect for squishing
* Move effects to separate classes (and make possible for adding effects with pk3s)
* Add option for spots life time
* Make all effects optional
* Rework gibing calculation (make something similar to UGibs)
* Make an option for wounds positioning on voxel corpses
* Textured particles for wound blood (not sure about this one)
* Utilization of sounds from loaded gore mods (similar to what was done in the cleaning mod)
* Wounds pitch on dead bodies from their initial position
* Big splash on entity death
* Change vanilla monsters blood color on sapwn
