# MLEditorUnrealEngine
Multiplayer Level Editor for Unreal Engine

## Preview

[Demo Video](https://youtu.be/1ATR_H6iU7c)

<img src="Documentation/Images/showcase_4players.png" width=100% height=100% />

<img src="Documentation/Images/showcase_ui.png" width=100% height=100% />

## Features

- Gizmo to change location, rotation and scale (with snapping and transform space : world or local)
- Save and load all objects in save files, you can also load the save within Unreal Engine
- UI to see and set transform, change gizmo settings with buttons
- Host and join session to create together, objects are synced on connection
- Switch from editorPawn to another pawn whenever you want

## Controls

- Left Click : select object, hold shift to select multiple, hold ctrl to deselect
- Right Click : hold it to move the camera, use WASD and QE to move
- Tab : deselect all objects
- Space : change transform mode (location, rotation, scale)
- Escape or P : open menu
- Ctrl + C, Ctrl + V, Ctrl + D, Alt + LeftClick : duplicate objects
- C : create cube
- R : round transform depending on snapping settings
- F : focus on selected object
- O : switch pawn
- T : change gizmo transform space (world or local)

## Credits

Thanks to [robinwood3d](https://github.com/robinwood3d) for his gizmo blueprints which you can find here : [UnrealTransformGizmo](https://github.com/robinwood3d/UnrealTransformGizmo)
