## ICustomGui.md


#### Usage     
<br>

<pre>
API.createCustomGui(int id, int width, int height, boolean pauseGame)
</pre>

<br>
<br>

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
int | getID() | Returns gui ID
int | getWidth() | Returns gui width
int | getHeight() | Returns gui height
List\<[ICustomGuiComponent](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiComponent.md)\> | getComponents() | Returns a list with all gui components
List\<[IItemSlot](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiItemSlot.md)\> | getSlots() | Return a list with all gui slots 
PlayerDataScript | getScriptHandler() | Returns playerDataScript
void | setSize(int width, int height) | Set gui size
void | setDoesPauseGame(boolean pauseGame) | Set whenever the gui will stop the game or not (only singlePlayer)
void | setBackgroundTexture(String resourceLocation) | Set gui background texture
String | getBackgroundTexture() | Returns gui background texture
IButton | addButton(int id, String label, int x, int y) | Add a new button to the gui
IButton | addButton(int id, String label, int x, int y, int width, int height) | Add a new button to the gui
IButton | addTexturedButton(int id, String label, int x, int y, int width, int height, String texture) | Add a textured button to the gui
IButton | addTexturedButton(int id, String label, int x, int y, int width, int height, String texture, int textureX, int textureY) | Add a textured button to the gui
ILabel | addLabel(int id, String label, int x, int y, int width, int height) | Add a label to the gui
ILabel | addLabel(int id, String label, int x, int y, int width, int height, int color) | Add a label to the gui
