# KSP-AGuS (Automatic Guidance System)
> The goal of this project is to have a flexible and functional auto pilot for krpc that will be able to navigate any given Vessel to the desired orbit or location. The program structure was designed with compatibility and extensions in mind and is therefore easy to change according to personal needs. 
I for one never planned this to be an alternative way of playing the game, but rather used it to learn more about programming in my free time. 
<p>

For more Information see the [wiki](https://github.com/Nik4053/KSP-KRPC-AGuS-Automatic-Guidance-System/wiki) or visit the [docs](https://nik4053.github.io/KSP-AGuS-Automatic-Guidance-System/)
## Overview
The AGuS allows you to automaticly launch any given rocket into a desired Orbit.

If you would rather like to create the maneuver nodes yourself you can use the "execute node" function of this software.

The AGuS is still in development, so errors, bugs, or missing features are to excpect. If you have understanding of orbital dynamics, or want to help improve the code performance, readability, design, etc. your support will be more than welcome.

## Installation
 1. You need to install krpc into the ksp gamedata folder either manually or with ckan. See the recommended versions [here](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/wiki#11-versions)
 2. Download and unzip the newest version of [AGuS](https://github.com/Nik4053/KSP-KRPC-AGuS-Automatic-Guidance-System/tree/master/user)
 3. Change the settings.ini inside the "settings" according to your needs. See the [wiki](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/wiki#41-settingsini)
 4. Change and add missions inside the "settings/missions/" folder. See the [wiki](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/wiki#42-missionini)
 5. Start KSP and choose a vessel you want.
 6. Startup the Krpc server
 5. Start the AGuS.jar file and hit connect.
 
 Note that whenn changing the vessel the AGuS has to be restarted too.
 
## Development setup
 1. Get the [krpc-java-x.x.x.jar](http://forum.kerbalspaceprogram.com/index.php?/topic/62902-130-krpc-remote-procedure-call-server-v039-14th-june-2017/) + all dependencies (protobuf + javatuples) + [NHLogJava](https://github.com/Nik4053/NHLogJava)
 2. Download the newest version of the AGuS library [here.](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/tree/master/libs) See the README there for more information.
 3. (optional) if you do not want to use this library, but rather want to change, improve and add content to it you can download the sourcecode from the src [folder](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/tree/master/dev)

## Information for developers
 AGuS can also be used as a library extending the existing krpc library with usefull additions like advanced vessel info, saving of orbits,  automatic staging, automatic node execution etc. That allows easy control, implementation and exstension possibilities, but also comes at the cost of a higher network usage.
 
## Dependencies
* krpc and its dependencies
* [NHLogJava](https://github.com/Nik4053/NHLogJava)
* see the [wiki](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/wiki#11-versions)

## Release History
* 0.8.0
    * First public release
    
## Credits
* Niklas Heidenreich (Nik4053) 
* Jakob Emmerling (Jack-em)

## Downloads
* [AGuS plug and play executable](https://github.com/Nik4053/KSP-KRPC-AGuS-Automatic-Guidance-System/tree/master/user)
* [AGuS precompiled library](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/tree/master/libs)
* [AGuS source code for development](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/tree/master/dev)

## Future plans
* inclination change
* better vessel orientation
* raspberry support
* displayOtron Hat support
* planetary transfers
* rover support
* landing
* docking
* ballistic transfer

## License
[See LICENSE.md](https://github.com/Nik4053/KSP-AGuS-Automatic-Guidance-System/blob/master/LICENSE)
