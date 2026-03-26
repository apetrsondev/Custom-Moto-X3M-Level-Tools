# CUSTOM LEVEL TOOL
run with 
```
python make-level.py
```

# CONTROLS
you make objects by selecting vertices and then pressing buttons to create objects.

The controls are as follows:

| # OF VERTICES SELECTED | KEYBIND | ACTION | DESCRIPTION |
| ---------------------- | ------- | ------ | ----------- |
| v = 1 | N | Pivot Joint | Joint that spins freely |
| v = 1 | M | Motor | Joint that will spin at a set speed | 
| v = 1 | T | TNT | TNT |
| v = 2 | F | Finish area | Area that will finish the map |
| v = 2 | T | Trigger | Triggers any *action item* with the same ID |
| v >= 2 | ENTER | Landscape/Ground | the floor of maps, the camera will always expand to include it | 
| v >= 2 | P | Pipe | Similar to ground but does not extend downwards |
| v >= 2 | D | Physics object | Will move with physics, can be moved with Move Path and pinned in place with any Joint |
| v >= 2 | M | Move Path | Will move physics objects along a set path | 

## Other Controls
| KEYBIND | ACTION | DESCRIPTION |
| --- | --- | --- |
| L-Ctrl + S | Save to File | Saves to the file that was selected at the start of the program | 
| L-Ctrl + Z | Undo | Undoes the previous action |



# Troubleshooting
make sure all dependencies are installed:

```
pip install pygame
pip install numpy
pip install easygui
```
