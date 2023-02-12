# csgo-config
My config for CS:GO.

Install
---
The first way:
1. Open Steam userdata folder - `C:\Program Files (x86)\Steam\userdata\<user_id>\730\local\cfg`.
2. Remove an existing `config.cfg` from the folder.
3. Place my config in the folder and rename it to `config.cfg`.

The second way:
1. Place my config to `steamapps\common\Counter-Strike Global Offensive\csgo\cfg` folder.
2. Press the `~` key in the main menu, and that will open the console.
2. Type `exec <my_config_name>` command.
3. Press Enter to apply my config.

Launch Options
---
```
-threads 6 +fps max 0 -tickrate 128 -high -novid +cl_interp 0 +cl_interp_ratio 1 +cl_updaterate 128 cl_cmdrate 128 +cl_forcepreload 1
```

To sync a monitor with FPS you may add the following options:

```
-freq <number> -refresh <number>
```
where `<number>` is HZ of your monitor. For example: `60`, `120`, `144`, `165` or any other.
