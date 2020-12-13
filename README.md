# lemonbar-config

This is my custom lemonbar config with a somewhat irc support using fifo!

It would be the best if whoever is gonna use this config knows even a little shell scripting because you wont be able to use it if you dont.

I reccomend putting all the scripts into a directory in your path like /usr/bin/ or .local/bin.

To have something like irc support you need to create a script that will output something desired to the fifo file.

example:
```
keybindig && script > /tmp/panel-top-fifo
```

backlight, volume and mpd player state are irc ones in this config.

This script also has support for a lot of things like amd cpu temp and mpd currentcurrent  song

screenshot :

![](https://raw.githubusercontent.com/CroLinuxGamer/Photos/master/lemonbar.png)
