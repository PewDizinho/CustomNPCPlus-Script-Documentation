## IDBCPlayer

### ♦️ Atention!
> These methods are NBT simplifications! Any misplaced value placed here could result in the player's date or even the world's date being corrupted! Don't use it if you don't have experience, test it on singleplayer worlds before putting it on your server!

### ? Reference
* Stat = (str - dex - con - wil - mnd - spi)
* Race = 0: Human, 1: Saiyan, 2: Half-Saiyan, 3: Namekian, 4: Arcosian
* Class = 0: Martial Artist, 1: Spiritualist, 2: Warrior

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | setStat(String stat, int value) | Set player's stat
void | setRelease(byte release) | Set player's release power
void | setBody(int body) | Set player's body
void | setStamina(int stamina) | Set player's stamina
void | setKi(int ki) | Set player's ki
void | setTP(int tp) | Set player's Training Points
void | setGravity(float gravity) | Set player's gravity
void | void setHairCode(String hairCode) | Set player's hair code
void | setExtraCode(String extraCode) | Set a custom extra data on player's nbt
void | setForm(byte form) | Set player's form
void | setForm2(byte form2) | Set player's form2
void | setPowerPoints(int points) | Sets the player's Arcosian power reserve
void | setAuraColor(int color) | Set player's aura color
void | setFormLevel(int level) | Set player's form level
void | setSkills(String skills) | Set player's skills
void | setJRMCSE(String statusEffects) | Set player's dbc effect
ScriptItemStack[] | getInventory() | Returns player's dbc extra inventory slots
String | getSkills() | Returns player's skills
String | getHairCode() | Returns player's hair code
String | getExtraCode() | Returns the custom extra data
String | getJRMCSE() | Returns player's dbc effect
int | getKillCount(String type) | Types: (evil -  good - neutral - all)
int | getPowerType() | Returns player's power type
int | getRace() | Returns player's race
int | getFormLevel() | Returns player form Level
int | getAuraColor() | Returns player's aura color
int | getPowerPoints() | Returns player's Arcosian power reserve
int | getTP() | Returns player's Training Points
int | getKi() | Returns player's ki
int | getStamina() | Returns player's stamina
int | getBody() | Returns player's body
int | getStat(String stat) | Returns the player's stat
float | getGravity() | Returns player's gravity
byte | getDBCClass() | Returns player's dbc class
byte | getForm2() | Get player's form2
byte | getForm() | Returns player's form
byte | getRelease() | Returns player's release power
boolean | isBlocking() | Returns true if player is blocking

