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
int | getPlayerInvX() | Returns player's inventory X
int | getPlayerInvY() | Returns player's inventory Y
PlayerDataScript | getScriptHandler() | Returns playerDataScript
void | setSize(int width, int height) | Set gui size
void | setDoesPauseGame(boolean pauseGame) | Set whenever the gui will stop the game or not (only singlePlayer)
void | setBackgroundTexture(String resourceLocation) | Set gui background texture
void | showPlayerInventory(int x, int y) | show player's inventory
void | removeComponent(int componentID) | Remove a gui component
void | updateComponent(ICustomGuiComponent component) | Update a component
void | update(IPlayer player) | Update player's gui 
boolean | getShowPlayerInv() | Returns true if player's inventory is on the gui
String | getBackgroundTexture() | Returns gui background texture
[ICustomGui](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/ICustomGui.md) | fromNBT(NBTTagCompound tag) | Create a customGui with NBT
[IButton](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiButton.md) | addButton(int id, String label, int x, int y) | Add a new button to the gui
[IButton](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiButton.md) | addButton(int id, String label, int x, int y, int width, int height) | Add a new button to the gui
[IButton](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiButton.md) | addTexturedButton(int id, String label, int x, int y, int width, int height, String texture) | Add a textured button to the gui
[IButton](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiButton.md) | addTexturedButton(int id, String label, int x, int y, int width, int height, String texture, int textureX, int textureY) | Add a textured button to the gui
[ILabel](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiLabel.md) | addLabel(int id, String label, int x, int y, int width, int height) | Add a label to the gui
[ILabel](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiLabel.md) | addLabel(int id, String label, int x, int y, int width, int height, int color) | Add a label to the gui
[ITextField](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiTextField.md) | addTextField(int id, int x, int y, int width, int height) | Add a text field to the gui
[ITexturedRect](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiTextureReact.md) | addTexturedRect(int id, String texture, int x, int y, int width, int height) | Add a textured react to the gui
[ITexturedRect](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiTextureReact.md) | addTexturedRect(int id, String texture, int x, int y, int width, int height, int textureX, int textureY) | Add a textured react to the gui
[IItemSlot](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiItemSlot.md) | addItemSlot(int x, int y) | Add a Item Slot to the gui
[IItemSlot](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiItemSlot.md) | addItemSlot(int x, int y, IItemStack stack) |  Add a Item Slot to the gui with a item on it
[IScroll](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiScroll.md) | addScroll(int id, int x, int y, int width, int height, String[] list) | Add a scroll to the gui
[ICustomGuiComponent](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiComponent.md) | getComponent(int componentID) | Get a gui component
List\<[IItemSlot](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiItemSlot.md)\> | getSlots() | Return a list with all gui slots 
List\<[ICustomGuiComponent](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/CustomGui/IGuiComponent.md)\> | getComponents() | Returns a list with all gui components
NBTTagCompound | toNBT() | Get gui's NBT







