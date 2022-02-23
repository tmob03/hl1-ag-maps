# hl1-ag-maps
Repository of all the hl1_bhop_X map sources I made.
You can play these maps by joining an https://openag.pro/ sourceruns kz server, and inputing agmap X into console to change the map to the desired map.

Maps not listed here were made by naz_atk, ask him for the sources if you so desire.


Or, you can compile the maps for yourself. Grab the VHLT v34 compiler tools here, https://twhl.info/wiki/page/Tools_and_Resources and below I'll list the compile parameters I use.

FAF, QE and LC:

CSG -cliptype simple
BSP -nohull2
VIS -full
RAD -extra -bounce 8 -smooth 120 -smooth2 120
You can also add -verbose and -chart to the tools for information about the compiles.

ST, RP:

CSG -cliptype normalized
BSP -nohull2
VIS -full
RAD -extra -bounce 8 -smooth 120 -smooth2 120
You can also add -verbose and -chart to the tools for information about the compiles.
