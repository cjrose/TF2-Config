# static's TF2 Config
I lost my config due to being dumb and resetting a hard drive without backing it up, so I'm eternalizing it here. This also doubles as making it really easy to share some of my settings with friends.

## Installation
If you want to try out my settings, you can do so by clicking `Code -> Download ZIP` above. Then follow these steps:
1. Navigate to `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom\` (or wherever your game is installed. This is the default game directory)
2. Unzip the contents of `TF2-Scripts.zip` into the `custom` folder.
3. Temporarily move any other configs you may have already in your `custom` folder
4. Restart your game if it's running

And that's it! Everything will run on it's own when you launch your game next.

## Usage
Included are several extensions I made to make some binds and functionality more accessible. You can feel free to disable these by adding `//` before the extensions you don't want to use in `TF2-Config/cfg/user/autoexec.cfg`. 

Some scripts also come with commands / keybinds you can use to use their functions. Some modules run on their own, such as `null_movement` and `class_swap` just changing what keys are bound to.

### Commands
* `regen`   -   Enables a regen script that will have you constantly regaining health and ammo so you can practice offline jumping. You may want to turn your volume down if the noise annoys you.
* `practice_rollout`    -   This binds (to default) `b` to be a key you can press on an offline server to restart the game and give you a buff to simulate rolling out in competitive.

### Binds
* `PGDN`    -   Shows all the keybinds for the Demo Support Extension
* `[`       -   Shows all the keybinds for the HUD Editing / Fixes Extension


## Credits
I didn't make all of these configs, some of them are stolen from TF.TV. Also, the underlying graphics settings are set through Mastercomfig's Module feature. Check `TF2-Config/cfg/user/modules.cfg` and [the docs](https://docs.mastercomfig.com/en/latest/customization/modules/) for more info.