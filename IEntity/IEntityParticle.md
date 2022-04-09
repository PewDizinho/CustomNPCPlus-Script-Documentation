## IEntityParticle



Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | IEntity.spawnParticle([IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) EntityParticle) | Spawn a Custom [IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md)
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setDirectory(string Directory) | Sets a new directory fot the particle
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md)| setHEXColor(int Color) | Sets the color of a particle from a [hex](https://imagecolorpicker.com) integer (0xFFFFFF by default)
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setAmount(int Amount) | Sets the amount of particles to spawn
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setPosition(double X, double Y, double Z) | Sets the position of the particle relative to the entity it's spawning on
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setPosition(double X, double Y, double Z, float gravity) | Sets the motion of the particle in the X Y and Z directions. The particle accelerates downwards when gravity > 0, and accelerates upwards when gravity < 0
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setScale(float scale1, float scale2, float scaleRate, int scaleRateStart) | scale1: The starting scale of the particle; scale2: The maximum/minimum scale of the particle if it grows/shrinks; scaleRotate: The reate at witch the particle grows/shrinks. Negative values shrinks the particle, a positive value expands it; ScaleRateStart: When the scale rate begins occuring, in ticks
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setAlpha(float apha1, float apha2, float aphaRate, int alphaRateStart) | alpha1: The starting transparency of the particle (0 to 1); alpha2: The maximum/minimum transparency of the particle if it grows/shrinks; alphaRate: The rate at wich thee particle fades or appears. Negative value makes the particle fade, positive values makes the particle appear; alphaRateStart: When the alpha rate begins occuring, in ticks
float | getRotationX1() | Get X1 rotation value
float | getRotationX2() | Get X2 rotation value
float | getRotationXRate() | Get X rate value
float | getRotationXRateStart() | Get X rate start value
float | getRotationY1() | Get Y1 rotation value 
float | getRotationY2() | Get Y2 rotation value 
float | getRotationYRate() | Get Y rate value
float | getRotationYRateStart() | Get Y rate start value
float | getRotationZ1() | Get Z1 rotation value 
float | getRotationZ2() | Get Z2 rotation value 
float | getRotationZRate() | Get Z rate value
float | getRotationZRateStart() | Get Z rate start value
void | setRotationX(float rotationX1, float rotationX2, float rotationXRate, int rotationXRateStart) | Sets rotation values about the X-axis
void | setRotationY(float rotationY1, float rotationY2, float rotationYRate, int rotationYRateStart) | Sets rotation values about the Y-axis
void | setRotationZ(float rotationZ1, float rotationZ2, float rotationZRate, int rotationZRateStart) | Sets rotation values about the Z-axis
void | setRotationX1(float rotationX1) | Set X1 Rotation
void | setRotationX2(float rotationX2) | Set X2 Rotation
void | setRotationXRate(float rotationXRate) | Set X1 Rotation rate
void | setRotationXRateStart(int rotationXRateStart) | Set X1 Rotation rate start
void | setRotationY1(float rotationY1) | Set Y1 Rotation
void | setRotationY2(float rotationY2) | Set Y2 Rotation
void | setRotationYRate(float rotationYRate) | Set Y1 Rotation rate
void | setRotationYRateStart(int rotationYRateStart) | Set Y1 Rotation rate start
void | setRotationZ1(float rotationZ1) | Set Z1 Rotation
void | setRotationZ2(float rotationZ2) | Set Z2 Rotation
void | setRotationZRate(float rotationZRate) | Set Z1 Rotation rate
void | setRotationZRateStart(int rotationZRateStart) | Set Z1 Rotation rate start

