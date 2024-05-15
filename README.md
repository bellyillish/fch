# GAMMA-Tuner for Fillable Canteens
Minimod that re-tunes the balance of "Fillable Canteens" to better fit GAMMA. I made this because I like the idea but think the original mod is a little too generous for GAMMA's balance.

### Things I wanted to change about "Fillable Canteens":
It makes these changes to water flasks (among others):
- Gives flasks 10 uses (instead of 3).
- Each use reduces thirst by -1.15 (instead of -2.98).

So each flask contains more water, but each use recovers less thirst. (Balance aside, the number of drinks you have to take -- a.k.a. the number of drink animations you have to sit through -- can get tedious).

It also adds purification tablets that you can buy to instantly purify dirty water. But purification tablets have a base cost of 600RU for 10 tablets, so you can have a full flask of clean water for 1/10 the cost of buying one.

It also includes "Campfire Roasting". which lets you boil water at any campfire for free. Boiled water has almost the same thirst reduction (-1.0). The only drawback is a tiny amount of radiation (+0.0075).

### How this mod changes those things:
- You can add purification tablets only to boiled water. So in other words it turns dirty->boiled->purified water into a progression thing. You have to collect dirty water, boil it, then add a purification tablet to make it completely safe for drinking.
- Reverts ALL flask settings back to GAMMA defaults (3 uses, -2.98 thirst per use, etc.)
- Gives purification tablets to base cost of 1316RU for 3 uses.
- Dirty water gives you 1/3 the thirst reduction of clean water (-0.99), and 3x the radition of the original mod (+0.025, about as many rads as raw dog meat).
- Boiled water gives you 2/3 the thirst reduction of clean water (-1.98), and half the radiation of dirty water (+0.0125, rad-wise between cooked dog and dog stew).
- Disables the "roasting" part of Campfire Roasting so that you can only boil water and still need cooking kits to cook meat (optional but recommended).

The net effect is that collecting, boiling, and purifying your own water is about 2/3 the cost of buying a flask of water. It's a small savings for the extra effort that you probably won't care about aside from very early on. But the real point is to let you be self-sufficient in the field (but without just giving away free water). Bottled water meanwhile remains higher-tier than all 3 with more thirst reduction and better buffs.

## Installation
1. Download and install Fillable Canteens: https://www.moddb.com/mods/stalker-anomaly/addons/fillable-canteens-20. During installation:
    1. Tick "Campfire Roasting" (or else you won't be able to boil the water)
    1. Untick "Water Pumps" (or else there's not really a point to this)
2. Either move it above (lower priority) "350-Ledge Grabbing - Demonized", or find the file "demonized_geometry_ray.script" in the Fillable Canteens mod folder and set it to "Hide". (Things seem to work OK without this step, but I assume this script was updated when Ledge Grabbing was released for a good reason).
3. Install this mod and put it below (higher priority) Fillable Canteens. During installation:
    1. Tick "00 No Roasting Meat (Recommended)" unless you don't want this mod to disable the ability to roast meat.

### Notes
- This is public domain.
- The current settings/balance feel good to me, but I'm definitely open to other opinions and futher tweaks. If you try it let me know what you think.
- I had the idea of not leaning on "Campfire Roasting" at all, and instead creating my own "Boil Water" functionality that still required a cooking kit (just to add an extra step/barrier and make it more similar to cooking). I haven't really looked into this, but if there's interest I might give it a go.
