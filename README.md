# Apex Configs
configs optimized for highest fps posible

## Start up parameters
You can add these in origin or at the end of your path in your desktop shortcut(helps if you have multiple accounts)


```-novid +fps_max unlimited -refresh 240 -dev -console -preload -forcenovsync -fullscreen -high +exec autoexec.cfg```


```-refresh``` add the hz of you monitor's refreshrate.
```-dev -console``` are to enable developer console and is cheat protected.
```-preload``` could cause stutters on some old systems. but will increse preformance on others.
```-high``` is to set the game process in high priority.

## Locations

```videoconfig.txt``` and ```settings.cfg``` go in 

```C:\Users\ (user) \Saved Games\Respawn\Apex\local```

```videoconfig.txt``` should be set to read only. as making a video change in game will result in the file to reset.

```profile.cfg``` belongs in ```C:\Users\(user)\Saved Games\Respawn\Apex\profile\``` 

```autoexec.cfg```,   ```bind.cfg```, and ```console.cfg```'s belong in the instalations path ```Apex/cfg/```

example ```C:\Program Files (x86)\Origin Games\Apex\cfg\autoexec.cfg```

## Frame caping

In-Game fps cap ```max_fps``` only works up to 144fps.

Use RTSS for framerate caping as like most other game engines caps nothing beats RTSS in frametime consistancy. I wish there was an equivalent that was open source

https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html

## Included binds

Included binds in ```binds.cfg``` that is exicuted in ```autoexec.cfg```

- ```~``` and ```DELETE``` Keys will re-execute ```autoexec.cfg```
- ```END``` toggles ```cl_showpos 0 1```
- ```HOME``` toggles ```cl_showfps 0 4```
- ```]``` toggles ```cl_fovScale 1.275 1.55``` (90-110) a fix for bloodhounds ult if you get massive frame drops. or for useing scopes range finder as the ticks are bugged on fov diffrent then 90.

## Other things notable 

- Binding a third key is simple and can be done in ```*.cfg```. for examples reference ```settings.cfg```. Insted of a ```0``` or a ```1``` at the end of the bind command seqence you will need to put a ```2```. For a 4th bind of an action you will need a ```3``` etc. example: ```bind "ALT" "+jump" 2```. This would make the 3rd bind for jump ALT. and this should be put in ```binds.cfg```.

- exicuting the autoexec.cfg while in a match ```DEL``` key will apply visual diffrences. these visual diffrences are optimized atm for Max Dark Boost options on gaming monitors.

- some command settings only work at startup in ```videoconfig.txt``` like LOD. and others like FOV may work as a ingame bind.
 
## to do

- compare against mendo's autoexec when released
- clean up cfgs
