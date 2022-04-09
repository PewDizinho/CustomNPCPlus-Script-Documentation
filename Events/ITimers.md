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
int | ticks(int id) | Gets the remaining ticks in the timer that matches this id
int | maxTicks(int id) | Gets the maximum ticks that must elapse for the timer that matches this id to finish
boolean | has(int ID) | Returns true if the Entity has a running timer with the ID
boolean | repeats(int id) | Returns true if the timer with the given id is set to repeat, false otherwise
void | start(ind ID, int Lenght, boolean repeat) | Start a new timer with the ID (If the Entity alredy has a timer with the same ID running, the console will throw an error message
void | forceStart(ind ID, int Lenght, boolean repeat) | Start a new (Or restart a running) timer 
void | stop(int ID) | Stop a running timer
void | reset(int ID) | Reset a running timer
void | clear() | Remove all running timers
void | setTicks(int id, int ticks) | Sets the remaining ticks in the timer that matches this id
void | setMaxTicks(int id, int ticks) | Sets the maximum ticks that must elapse for the timer that matches this id to finish
void | setRepeats(int id, boolean repeat) | Sets whether the timer with the given id should repeat. If true, the timer will repeat, and not repeat otherwise
