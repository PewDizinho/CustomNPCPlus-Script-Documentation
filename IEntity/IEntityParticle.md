## IEntityParticle



Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | IEntity.spawnParticle([IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) EntityParticle) | Spawn a Custom [IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md)
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setDirectory(string Directory) | Sets a new directory fot the particle
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md)| setHEXColor(int Color) | Sets the color of a particle from a [hex](https://imagecolorpicker.com) integer (0xFFFFFF by default)
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setAmount(int Amount) | Sets the amount of particles to spawn
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setPosition(double X, double Y, double Z) | Sets the position of the particle relative to the entity it's spawning on
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setPosition(double X, double Y, double Z, float gravity) | Sets the motion of the particle in the X Y and Z directions. The particle accelerates downwards when gravity > 0, and accelerates upwards when gravity < 0
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setScale(float scale1, float scale2, float scaleRate, int scaleRateStart) | scale1: The starting scale of the particle; scale2: The maximum/minimum scale of the particle if it grows/shrinks; scaleRotate: The reate at witch the particle grows/shrinks. Negative values shrinks the particle, a positive value expands it; ScaleRateStart: When the scale rate begins occuring, in ticks
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setAlpha(float apha1, float apha2, float aphaRate, int alphaRateStart) | alpha1: The starting transparency of the particle (0 to 1); alpha2: The maximum/minimum transparency of the particle if it grows/shrinks; alphaRate: The rate at wich thee particle fades or appears. Negative value makes the particle fade, positive values makes the particle appear; alphaRateStart: When the alpha rate begins occuring, in ticks 
