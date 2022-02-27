
## IScriptOverlay

<br>
WIP
<br>

Modifier and Type | Method | Description
------- | ------------- | -------------------------------------------------------------
int | getID() | Returns the components ID
int | getPosX() | Returns the components X position
int | getPosY() | Returns the components Y position
int | getPosZ() | Returns the components Z position
int | getColor() | Returns the component's color as an integer
int | getType() | Returns the component's type as an integer: 0 - textured rectangle   1 - label   2 - line
float | getAlpha() | Returns the component's alpha
float | getRotation() | Returns the component's rotation
void | setID(int ID) | Sets the components ID to the given integer
void | setPos(int X, int Y) | Sets the components X & Y positions to the given integers, and returns the updated component.
void | setAlignment(int [alignment](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/Overlay/ScriptOverlayComponent.md#alignments)) | Sets the component's alignment, based on the given integers
void | setColor(int color) | Sets the component's color as a hex color
void | setAlpha(float alpha) | Sets the component's alpha from 0 to 1
void | setRotation(float rotation) | Sets the component's rotation
[alignment](https://github.com/PewDizinho/CustomNPCPlus-Script-Documentation/blob/main/Overlay/ScriptOverlayComponent.md#alignments) | getAlignment() | Returns the component's alignment




## Alignments 
0 - `Top-Left Corner`

1 - `Top-Center`

2 - `Top-Right Corner`

3 - `Left Edge`

4 - `Center`

5 - `Right Edge`

6 - `Bottom-Left Corner`

7 - `Bottom-Center`

8 - `Right-Left Corner`
