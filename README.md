# FlyPE [![HitCount](http://hits.dwyl.com/AGTHARN/FlyPE/master.svg)](http://hits.dwyl.com/AGTHARN/FlyPE/master) [![GitHub license](https://img.shields.io/github/license/AGTHARN/FlyPE)](https://github.com/AGTHARN/FlyPE/blob/master/LICENSE)
![flypeicon](https://user-images.githubusercontent.com/63234276/82717419-895d2380-9cce-11ea-9d7e-0981d91c75fa.jpg)
+ FlyPE is a fly plugin for pocketmine that allows you to fly in survival mode when you run the fly command! You can choose to allow fly to be used or not allow fly to be used in selected worlds in the config! And there are more features listed below!

# How do I use it?
To use it, [download the latest phar](https://poggit.pmmp.io/ci/AGTHARN/FlyPE/FlyPE) and put it in the plugins folder. Restart your server and use /fly ingame to toggle flight! Make sure to also check out the config in your plugins data folder!

# Requirements
+ [EconomyAPI](https://poggit.pmmp.io/p/EconomyAPI/5.7.2)
(Only required if you have the payforfly config on)

# Features
- [x] Blacklist fly in selected worlds
- [x] Whitelist fly in selected worlds
- [x] Option to disable fly during PVP
- [x] Option to disable fly after joining
- [x] Creative can't toggle fly
- [x] Toggle fly for others
- [x] A fly UI to toggle flight
- [x] A permission to bypass the world checks
- [x] Option to enable buying of fly
- [ ] Temporal fly time
- [ ] Customisable messages

# Permissions
+ **flype.command** - Allows player to run the /fly command (Default: OP)
+ **flype.command.others** - Allows player to run /fly on others (Default: OP)
+ **flype.command.bypass** - Allows player to bypass checks when switching to a different world (Default: OP)

# Config File
You can find the config file [here](https://github.com/AGTHARN/FlyPE/blob/master/resources/config.yml)!

# Plugin Info
+ Name: FlyPE
+ Author: AGTHARN
+ Version: 1.0.0
+ Api: [3.0.0, 4.0.0]
