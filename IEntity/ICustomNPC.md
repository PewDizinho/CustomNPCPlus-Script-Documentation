## ICustomNPC

<br>

**extends [ScriptLivingBase](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IEntityLivingBase.md)**
<br>
**ICustomNPC entity on [official documentation](http://www.kodevelopment.nl/customnpcs/api/1.7.10/noppes/npcs/scripted/ScriptNpc.html)**
<br>

<br>

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | ICustomNPC.setVisibleTo([IPlayer](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IPlayer.md) Player, boolean Visible) | Change the npc visibility to a specific [IPlayer](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IPlayer.md)
void | ICustomNPC.isVisibleTo([IPlayer](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IPlayer.md) Player) | Returns true if the NPC has had its visibility toggled for a specific [IPlayer](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IPlayer.md)
[ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md) | ICustomNPC.getTimers() | Used to manipulate an npc's timers
