## IEntityParticle



Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
void | IEntity.spawnParticle([IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) EntityParticle) | Spawn a Custom [IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md)
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setDirectory(string Directory) | Sets a new directory fot the particle
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md)| setHEXColor(int Color) | Sets the color of a particle from a [hex](https://imagecolorpicker.com) integer (0xFFFFFF by default)
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setAmount(int Amount) | Sets the amount of particles to spawn
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setPosition(double X, double Y, double Z) | Sets the position of the particle relative to the entity it's spawning on
[IEntityParticle](https://github.com/PewDizinho/CustomNPC-Script-Documentation/blob/main/IEntity/IEntityParticle.md) | setPosition(double X, double Y, double Z, float gravity) | Sets the motion of the particle in the X Y and Z directions. The particle accelerates downwards when gravity > 0, and accelerates upwards when gravity < 0
