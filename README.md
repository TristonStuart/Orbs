# Orbs
An agario based game, open source, and built with tons of plugins.
### Status : Re-Write (Not Working) ; Re-Write Percent : %10
### Working Version : https://github.com/TristonStuart/Orbs/tree/70a4308a3c63f401fb17b5474ff77bca919d0ddb (Update v0.3 is the last working release. Tweeking to the npm packages locations may be made if you arent using npm and dont have some packages downloaded. I will publish a FULL working update on version 0.3, called 0.3.1, and add a link here while I work on a re-write)

## Plugins
Plugins are drag and drop. Drag the plugin's folder into the Orbs Plugins Folder. <br>
Plugins will automatically be loaded in on startup. <br>
Plugins will have full acess to the game, game engine, game physics, console, and other plugins. <br>
Plugins may make themselves Private to avoid interference from other plugins. (Good For User Data Plugins) <br>
I recommend you install plugins only featured on ouir plugin page and from reputable plugin makers.

## Mini Docs
### Radius to Mass Conversion (And Back)
Radius is bassed on Mass, both can be transitioned from one unit to another. <br>
Radius is used for mathematical calculations and client rendering. <br>
Mass is used by the Server, Server Operator, Client, Users, and Plugin Makers as a common unit of measurement. <br>
Mass is easibly understood and is factored into calculations like eating cells and players.<br>
RADIUS to MASS => Math.floor((Math.PI * radius * radius) / 100)<br>
MASS to RADIUS => Math.round(Math.sqrt((mass * 100) / Math.PI))<br>
### (INCOMPLETE)