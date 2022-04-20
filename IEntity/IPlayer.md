## IPlayer	 

<br>

**extends [ScriptLivingBase](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IEntityLivingBase.md)**
<br>
**IPlayer entity on [official documentation](http://www.kodevelopment.nl/customnpcs/api/1.7.10/noppes/npcs/scripted/ScriptPlayer.html)**

<br>

<br>

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | setPosition(int X, int Y, int Z, int dimensionID) | Teleports a IPlayer to the position in the dimension matching the given dimension ID
void | setRotation(int Yaw, int Pitch) | Changes the player's rotation
void | setHunger(float hunger) | Sets the player's hunger to the amount given
void | setSaturation(float saturation) | Sets the player's saturation to the amount given
void | showCustomGui([ICustomGui](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/ICustomGui.md) gui) | Show a custom Gui to the player
float | getHunger() | Returns the player's current hunger level
float | getSaturation() | Returns the player's current saturation level
int | getDimention() | Gets the dimensionID of the player
boolean | checkGUIOpen() | Checks whether the player has a GUI open, Sends a packet from the server to client, updates PlayerData. Takes two function calls on two separate ticks to return the correct value
[ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md) | getTimers() | Used to manipulate an player's timers
[IDBCPlayer](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IDBCPlayer.md) | getDBCPlayer() | Get the [IDBCPlayer](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IDBCPlayer.md) from the player ([Dragon Block C](https://main.jingames.net/minecraft-mods/dragon-block-c/) required)


