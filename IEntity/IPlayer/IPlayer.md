## IPlayer

<img src="exemplo-image.png" alt="exemplo imagem">

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | setPosition(int X, int Y, int Z, int dimensionID) | Teleports a IPlayer to the position in the dimension matching the given dimension ID
void | setRotation(int Yaw, int Pitch) | Changes the player's rotation
int | getDimention() | Gets the dimensionID of the player
boolean | checkGUIOpen() | Checks whether the player has a GUI open, Sends a packet from the server to client, updates PlayerData. Takes two function calls on two separate ticks to return the correct value
[ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md) | getTimers() | Used to manipulate an player's timers
[IDBCPlayer](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IDBCPlayer.md) | getDBCPlayer)() | Get the [IDBCPlayer](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IDBCPlayer.md) from the player (Dragon Block C required)
