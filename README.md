# Blender Playground

## Introduction

This is just a repo to fool around with Blender 3D modelling.

## Shortcuts

### Blender

* CTRL+S: cursor control options
* A: select all
* SHIFT+A: add mesh primitive
* G((+z|y|z)(+SHIFT)): transform position (along axis / excluding axis)
* R(+z|y|z): rotate (along axis, double press axis for local axis)
* S(+z|y|z): scale (along axis, double press axis for local axis)
* I(+x|y|z): inset (along axis, double press axis for local axis)
* CTRL+A: apply menu
* CTRL+B: bevel (scroll up or down to increase bevel)
* E(+x|y|z): extrude (along axis)
* W: change select tool type (circle, square, lasoo, etc)
* CTRL+Z: undo
* CTRL+Y: redo
* N: bring up right-side toolbar
* T: open left-hand toolbar
* SHIFT+Z: wireframe mode
* CTRL+M+(z|x|y): mirror (along axis)
* SHIFT+D: copy
* ALT+D: copy linked
* CTRL+D: link/transfer menu
* CTRL+P: (with multiple selected scene objects) assign objects to children of a parent
* Z: render menu
* NUMPAD 5: orthographic mode
* ALT+LEFT-MOUSE-CLICK: select vertex or edge loop
* CTRL+SHIFT+B: bevel a vertex in edit mode
* CTRL+(1|2): add subdivision modifier
* CTRL+R: add loop cut
* SHIFT+S: snap pie menu
* CTRL+X: dissolve edge
* L: select linked geometry
* G+G: slide vertex along edge
* CTRL+(numpad/): slice on particular model through the second
* CTRL+(numpad+): union boolean between two primitives
* H: hide selected object
* L: select all linked over cursor
* P: separate by selection

#### Camera/viewport

* MMB: rotate viewport
* SHIFT+MMB: pan viewport
* SHIFT+~: WASD mode
* NUMPAD 0: look through camera (camera mode)
* SHIFT+~ (in camera mode): manipulate the camera in FPS mode
* NUMPAD 1(+CTRL): look down +Y axis (CTRL inverts)
* NUMPAD 3(+CTRL): look down -X axis (CTRL inverts)
* NUMPAD 7(+CTRL): look down -Z axis (CTRL inverts)
* NUMPAD 9: rotate camera 190 degrees, effectively flipping it to look down the opposite axis

### MACHIN3tools

* Tab: change mode

## Common problems

* Cursor was accidentally misplaced: `Shift+S` -> `Cursor to World Origin`
* Shading goes ballistic with modifiers for bevels and difference bools: always ensure difference bool modifiers are placed above difference bools in the modifier stack
* Bevel does not working some difference bools: disable clamp overlap option
* Mirror modifier works in an unexpected manner: check to see if rotations and scales have been applied to an object, and that the origin of the object is centred correctly

## Additional resources

### Useful addons

* [MACHIN3tools](https://gumroad.com/l/machin3tools)
* [MACHINE3tools docs](https://machin3.io/MACHIN3tools/docs/)

### Courses

* [BlenderBros](https://www.blenderbros.com/)
