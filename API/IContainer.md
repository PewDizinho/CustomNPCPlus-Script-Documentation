## IContainer

<br>
<br>


Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
int | count(IItemStack item, boolean ignoreDamage, boolean ignoreNBT) | Count how much Custom items have on the container
[IItemStack](http://www.kodevelopment.nl/customnpcs/api/1.7.10/noppes/npcs/scripted/ScriptItemStack.html)[]	| getItems()
net.minecraft.inventory.Container	| getMCContainer() | Expert users only
net.minecraft.inventory.IInventory	| getMCInventory()	| Expert users only
int	| getSize()	| Get container's size
[IItemStack](http://www.kodevelopment.nl/customnpcs/api/1.7.10/noppes/npcs/scripted/ScriptItemStack.html)	| getSlot(int slot)	| Get a IItemStack from a slot inside the container
void	| setSlot(int slot, [IItemStack](http://www.kodevelopment.nl/customnpcs/api/1.7.10/noppes/npcs/scripted/ScriptItemStack.html) item) | Set a item inside a slot
