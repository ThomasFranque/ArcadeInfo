# Arcade Info

All the info you need to develop a game for the arcade!

## Control Schemes

    Joysticks and buttons function as buttons being pressed, NOT axis ranging from -1 to 1.
    Diagonals are not registered as such.

### Left Inputs

| Arcade | Keyboard |
|--------|----------|
| | |
| Up     |    W     |
| Left   |    A     |
| Down   |    S     |
| Right  |    D     |
| | |
| Left Button     |    X     |
| Middle Button   |    C     |
| Right Button    |    V     |

### Right Inputs

| Arcade | Keyboard |
|--------|----------|
| | |
| Up     |    ↑     |
| Left   |    ←     |
| Down   |    ↓     |
| Right  |    →     |
| | |
| Left Button     |    J     |
| Middle Button   |    K     |
| Right Button    |    L     |

## Requirements

1. The game **must** exit on its own after losing / winning / timeout, or have an accessible exit button (`alt` + `f4` is not accessible).

2. Inside the Build folder, besides the executable, there should be an extra `.txt`
    and `.png`. 
    This is optional but recommended, since it will represent your game.

    - The `.txt` should contain only a brief description of the game with a maximum of 90 characters (spaces included).
  
    - The `.png` will be the icon that will appear in the arcade representing the game and should / is recommended to have an aspect ratio of 1:1.

## Final Notes

It should also be noted that the name of the build folder will be the name that will be shown in the arcade, not the name of the executable.

There is an example build folder in this repo: [Example Build folder link](https://github.com/ThomasFranque/ArcadeInfo/blob/master/ImTheExampleBuildFolder)
