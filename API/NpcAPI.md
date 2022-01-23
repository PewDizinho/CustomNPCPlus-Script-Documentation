## NpcAPI


#### Usage     
<br>

<pre>
API.executeCommand(world, "gamemode 0 " + player.getName());
</pre>

<br>
<br>


Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
[ICustomGui](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/tree/main/CustomGui) | createCustomGui(int id, int width, int height, boolean pauseGame) | Create a CustomGUI object
[ICustomNpc](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/ICustomNPC.md) | createNPC(new.minecraft.world.World world) | Doesnt spawn the npc in the world, just create a NPC object
[IEntity](http://www.kodevelopment.nl/customnpcs/api/1.7.10/) | getIEntity(Entity entity) | Returns a entity
IBlock | getIBlock(new.minecraft.world.World world, int x, int y, int z2) | Returns a IBlock
IContainer | getIContainer(IInventory inventory) | Returns a IContainer
IContainer | getIContainer(Container inventory) | Returns a IContainer
IItemStack | getIItemStack(ItemStack inventory) | Returns a IItemStack
IWorld | getIWorld(WorldServer server) | Returns a IWorld
IWorld | getIWorld(int worldID) | Returns a IWorld
IWorld[] | getIWorlds() | Returns a [array](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiEwKignsj1AhVRLLkGHf4tBL4QFnoECAwQAQ&url=https%3A%2F%2Fdeveloper.mozilla.org%2Fpt-BR%2Fdocs%2FWeb%2FJavaScript%2FReference%2FGlobal_Objects%2FArray%2F&usg=AOvVaw2Y5uA8WNuvhCxjMzgsUl-I) of all worlds
IDamageSource | getIDamageSource(DamageSource var1) | Returns IDamageSource
EventBus | events() | Returns a EventBus
File | getGlobalDir() | Returns a global file dir
File | getWorldDir() | Returns world file dir
boolean | IsAvailable() | Returns whenever CustomNPC is available
[NpcAPI](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/API/NpcAPI.md) | Instance() | Returns NpcAPI instace
void | executeCommand(IWorld world, string command) | Execute a command
String | getRandomName(inv var1, int var2) | 
INbt | getINbt(NBTTagCompound entityData) | Returns a INBT from a entityData
ScriptPlayer[] | getAllServerPlayers() | Returns a [array](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiEwKignsj1AhVRLLkGHf4tBL4QFnoECAwQAQ&url=https%3A%2F%2Fdeveloper.mozilla.org%2Fpt-BR%2Fdocs%2FWeb%2FJavaScript%2FReference%2FGlobal_Objects%2FArray%2F&usg=AOvVaw2Y5uA8WNuvhCxjMzgsUl-I) with all online player's online
ScriptItemStack | createItem(String id, int damage, int size) | Create a item
[EntityParticle](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | createEntityParticle(String directory) | Create a [EntityParticle](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/IEntity/IEntityParticle.md)
int | getServerTime() | Return total server time
