FeatherSpigot
===========

This is a fork of Paper 1.13.2, a high performance Minecraft server API. It is simply a project which backports Paper patches coded for 1.14+ to 1.13. It is designed for and used on a production server but is not intended for public use, so use at your own risk.

FeatherSpigot contains the following patches:

* Allow zombie turtle egg targeting to be configurable
* Performance improvement for Chunk.getEntities()
* Implement alternative item despawn rate
* Offset item frame ticking 
* Optimize DataWatcher
* Don't recalculate permissions on world change
* Do less work if we have a custom Bukkit generator
 
