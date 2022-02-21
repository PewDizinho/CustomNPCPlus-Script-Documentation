
## IScriptOverlay


#### Usage     
<br>

<pre>
API.createCustomOverlay(int id, int width, int height, boolean pauseGame)
</pre>

<br>
<br>

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
int | getID() | Returns gui ID
int | getWidth() | Returns gui width
int | getHeight() | Returns gui height
int | getPlayerInvX() | Returns player's inventory X
int | getPlayerInvY() | Returns player's inventory Y
[Components](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/Overlay/ScriptOverlayComponent.md) | getComponents() | Returns a list of the custom overlay's components
[Components](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/Overlay/ScriptOverlayComponent.md) | getComponent(int componentID) | Gets the component with the given id from the overlay
void | addTexturedRect(int id, String texture, int x, int y, int width, int height) | Adds a textured rectangle component to the overlay
void | addTexturedRect(int id, String texture, int x, int y, int width, int height, int textureX, int textureY) | Textured rectangle component with two additional texture offset parameters. The image's top-left corner in the png will be at (textureX, textureY) instead of the default (0,0)
void | addLabel(int id, String label, int x, int y, int width, int height) | Adds a label component to the custom overlay
void | addLabel(int id, String label, int x, int y, int width, int height, int color) |Adds a label component with the given text color to the custom overlay
void | addLine(int id, int x1, int y1, int x2, int y2, int color, int thickness) |Adds a line starting from (x1,y1) to (x2,y2) to the overlay
void | addLine(int id, int x1, int y1, int x2, int y2) | Adds a line starting from (x1,y1) to (x2,y2) with the given color and thickness to the overlay
void | removeComponent(int componentID) | Removes the component with this id from the overlay.
void | updateComponent(customOverlayComponent) | Updates the changes to the component. Updates cannot be seen until update(player) is called
void | update(player) | Sends overlay changes/overlay component changes to the player's client to be viewed
