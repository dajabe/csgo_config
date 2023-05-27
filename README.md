# csgo_config
 Configuration files for csgo

You will need to place these files in your config folder of your games local files. You can find in steam by right clicking "CS:GO > Manage > Browse local files". For me this folder was located here:

```
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg
```

Right click on "CS:GO > Properties > Launch Options" add:

```
+exec autoexec.cfg
```

## Bindings

There is a binding for

- Jumpthrow
- Mouse wheel jumping
- Grenades to letters under WASD
- Makes holding tab display net_graph
- Disable in game voip
- Toggle radar scale

## Practice

One of the main features of this config is easy setup of a practice server. Enable your developer console to take advantage of the aliased commands in the config.
Launch a "Game against bots" but select "No bots" in the top right hand corner.

Once the game launches open your developer console and run:

```
prac
```

This enables cheats and binds noclip to capslock along with a couple other useful settings for practicing nades.

Then you can run `nades` which will give you one of all the nades. Once you are done run the command `dc`. This will unbind noclip and disconnect you from the server.
