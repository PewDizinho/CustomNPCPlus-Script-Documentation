## ITimers


#### Usage     
<br>

<pre>
IEntity.getTimers();
</pre>

<br>
<br>



Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | start(ind ID, int Lenght, boolean repeat) | Start a new timer with the ID (If the Entity alredy has a timer with the same ID running, the console will throw an error message
void | forceStart(ind ID, int Lenght, boolean repeat) | Start a new (Or restart a running) timer 
void | stop(int ID) | Stop a running timer
void | reset(int ID) | Reset a running timer
void | clear() | Remove all running timers
boolean | has(int ID) | Returns true if the Entity has a running timer with the ID
