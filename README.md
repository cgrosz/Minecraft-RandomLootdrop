# Minecraft-RandomLootdrop

For more detail, watch this YouTube video: https://www.youtube.com/watch?v=wLWuTDcTQww

Plugins Required: Skript, skUniversal 

Works with GriefPrevention - The chest won't drop in claimed areas.
Works with Multiverse (or any other world plugin) - The chest will drop in the player's current world
Change lines 124 and 125 to the area where the crate should drop

USAGE: 
every command requires permission: minecraft.op
put the items you want to be loaded into the crate in your inventory (not hotbar)
run the /lootdrop new crateName command and it will create your first crate
/lootdrop view crateName will list all of the items in that crate
/lootdrop delete crateName will remove it completely
/lootdrop list will display all of the current crates you have

to actually drop a crate run /lootdrop crateName
keep in mind that even though you spawned the crate, it will not move while
the chunk is not loaded. To combat this, each time you drop a crate, it will send
the user a message asking if they want to TP to the crate. Just click on the text
in chat or run /lootdroptp. This is an easy way for an admin to get to the crate. 

/lootdrop help will display all of this information in game

You can only spawn 1 crate at a time (currently bugs with multiple crates at a time)
There's also a 30 second wait period after a crate lands until you can spawn another


