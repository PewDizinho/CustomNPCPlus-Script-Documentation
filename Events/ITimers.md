## ITimers



Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | [ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md).start(ind ID, int Lenght, boolean repeat) | Start a new timer with the ID (If the Entity alredy has a timer with the same ID running, the console will throw an error message
void | [ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md).forceStart(ind ID, int Lenght, boolean repeat) | Start a new (Or restart a running) timer 
void | [ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md).stop(int ID) | Stop a running timer
void | [ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md).reset(int ID) | Reset a running timer
void | [ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md).clear() | Remove all running timers
boolean | [ITimers](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/ITimers.md).has(int ID) | Returns true if the Entity has a running timer with the ID
