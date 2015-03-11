FSFuelSwitch4ALL 1.0

1. About

This is a simple patch of a few stock fuel tanks which:

- add ability to choose any stock propellant for them,
- enable surface attachment to some of them (both Stratus-V Mp tanks for example), allowing use of fuel lines on them when attached to non fuel cross-feed parts.


2. Requirements

KSP 0.90, not tested on other releases (it use parts'names which may have change since the clean-up).
Module Manager
Firespitter plug-in core (ONLY).
recommended: Goodspeed pump plug-in (help balancing content of tanks and 


3. how to install it (without CKAN) ?

Simply merge the provided GameData folder into your own, answer yes to any overwrite requests.


4. how to remove it (without CKAN) ?

Simply delete the folder Kerbice Group\Parts\Structural\LGB from you <KSP dir>\GameData directory.


5. CKAN install/removal

See CKAN documentation for detailled informations on installation and removal of this mod.


6. usage

Better to read Firespitter user documentation (if there is any :) ), but I think everything is self-explaining enough.
Choose some tanks, choose the right propellant for the engine(s), launch and enjoy.


7. Career mode

All prices & costs have been set to a dummy value, change it as you wish. Technology required have been set to match stock parts, you can also modify this if you believe it's not good enough.


8. know issues

[Module Manager issue]: using debug "reload DB" feature will KILL all the MM patches, so DO NOT use it !


9. crafts included

Some crafts are included in the archive (not installed with CKAN), just to show some of my crazy ideas.
Some of them may require other of my mods (low profile misc enines, simple wings, etc).


10. Under the hood

Propellants: LF=Liquid fuel, LF/Ox=LF + Oxydizer mixture, Mp=Monopropellant, Xe=Xenon Gas.

In order to get the "right" propellant amounts, I use existing and size equals tanks which hold various propellant like:
- Oscar-B (LF/Ox)
- FL-R10 (Mp)
- PB-X150 (Xe)
- mk2 fuselage short (both LF, LF/Ox)

Which gives the following formula (truncated values):

1 Mp = 8.75 Xe
1 LF/Ox mix = 6.282 Mp = 54.967 Xe
2 LF = 0.9 LF/1.1Ox
1 LF = 3.141 Mp = 27.483 Xe


11. How to add my preferred fuel tank ?

First, you MUST KNOW what you want to do and how to achieve it.
Then, take one in the file (the closest to you goal), adjust propellant amounts and masses and costs, check for which resource(s) to remove from part and you should be good to go.


A. changelog

1.0  /03/2015 first release


B. Contact

you can reach me directly on the KSP official forum as well as at JustinKerbice@hotmail.fr
If your question/concern is about how to use your paint program, convert a texture to a given format, how to create a rocket, how to crash Jeb's ship with style, or anything not DIRECTLY RELATED to this parts set, don't be surprised to wait forever for an answer.


C. license

This parts set and all its content, including this readme, is licensed under the whatever license 1.1, see included file for more details.
