## IPlayer



Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | IPlayer.setPosition(int X, int Y, int Z, int dimensionID) | Teleports a IPlayer to the position in the dimension matching the given dimension ID
void | IPlayer.setRotation(int Yaw, int Pitch) | Changes the player's rotation
int | IPlayer.getDimention() | Gets the dimensionID of the player
[ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md) | IPlayer.getTimers() | Used to manipulate an player's timers
boolean | IPlayer.checkGUIOpen() | Checks whether the player has a GUI open, Sends a packet from the server to client, updates PlayerData. Takes two function calls on two separate ticks to return the correct value
