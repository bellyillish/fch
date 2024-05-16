# Fillable Canteens GAMMA Tuner

Tunes Fillable Canteens to better fit GAMMA's balance. I made this because, while I like the idea, I think the original mod is a little too generous for GAMMA playthroughs.

### What Fillable Canteens does (vs. GAMMA):

The original mod gives flasks 10 uses (instead of 3) and makes each use reduce thirst by -1.15 (instead of -2.98). So while each flask contains more water, each use recovers much less thirst. Not a bad idea, but in practice the amount of sips you need to take (a.k.a. the number of drink animations you have to watch) can get tedious at times.

The original mod also adds purification tablets that you can buy to purify dirty water, but purification tablets have a base cost of only 600 for 10 tablets. This lets you "craft" a full flask of pure water for only 1/10 the cost of buying one.

And if you enable "Campfire Roasting" in the original mod, you can boil water at any campfire for free. But boiled water has almost the same thirst reduction as pure water (-1.0), the only drawback being a tiny amount of rads (+0.0075).

### What GAMMA Tuner does instead:

- You can now add purification tablets only to boiled water. In other words it turns dirty->boiled->purified water into a progression: you have to collect dirty water, then boil it, then add a purification tablet to make it 100% safe for drinking.

- Reverts ALL flask settings back to GAMMA defaults (3 uses, -2.98 thirst per use, etc.)

- Purification tablets now have a base cost of 1316 for 3 uses.

- Dirty water gives you 1/3 the thirst reduction of pure water (-0.99).

- Boiled water gives you 2/3 the thirst reduction of pure water (-1.98).

- Disables the "roasting" part of Campfire Roasting so that you can boil water *only* -- you still need cooking kits to cook meat (optional but recommended).

The net effect is that collecting, boiling, and purifying a flask of water is about 2/3 the cost of buying one. It's a small incentive for the extra effort that you probably won't care about aside from very early on. But the real point is to let you be self-sufficient in the field for water like you can be with food (but without giving water away for free). Meanwhile, bottled water remains a higher-tier luxury with it's increased thirst reduction and better buffs.

## Installation
1. Install Fillable Canteens with MO2: https://www.moddb.com/mods/stalker-anomaly/addons/fillable-canteens-20
    1. Tick "Campfire Roasting" (or else you won't be able to boil and purify water).
    2. Tick/Untick "Water Pumps" to your preference (pumps give dirty water at bases).
    3. See the next step for load order.

2. Install GAMMA Tuner for Fillable Canteens: [LINK_TO_LATEST_VERSION]
    1. Tick "00 No Roasting Meat" unless you want to roast meat.
    2. Tick "00 Patch demonized_geometry_xray.script" to overwrite's Fillable Canteens version of this script with the newer version that ships with Ledge Grabbing. Alternatively you can put Fillable Canteens above (lower priority) "350-Ledge Grabbing - Demonized" and then untick this.
    3. Put this below (higher priority) Fillable Canteens.

### Notes
- This is public domain. No credit is needed to use in other mods.

- If you try it let me know what you think -- I'm definitely open to opinions on how to further tweak the settings. It feels like it belongs to me, but I want to make sure the balance feels right.
