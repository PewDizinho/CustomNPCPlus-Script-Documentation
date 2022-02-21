
## IEntity

<br>
<br>
**ICustomNPC entity on [official documentation](http://www.kodevelopment.nl/customnpcs/api/1.7.10/noppes/npcs/scripted/ScriptEntity.html)**
<br>

<br>

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | setMotion(float x, float y, float z) | Sets motion of the entity to the given x, y, and z amounts. For players, any number above 10 usually does not work on servers
void | setPitch(float pitch) | Manipulates the pitch rotation (up/down) of the entity
float | getPitch() | Returns the pitch rotation (up/down) of the entity
boolean | isAirborne() | Returns true if the entity is in the air
