# Lab 2: Path Following Robot
Hello! This is Lab 2 of the Robotics course. In it we will make a robot that follows a path.

## Path to Robot

Now we'll do some robotics! You'll first need to add in a path. You can do this via the file menu `add` or by right clicking in the simulation and selecting `add`. Pick `path` and then `segment type`. This will place a simple path in the simulation. 

On the far left side click the `edit path` button as seen bellow

![img/editPath.jpg]

This will open up the path editor, it's a list of all the points in the path, just two for now. Select `Path point 1`, right click it, and select `Insert new control point after selection`. Now we have three points! To move any particular point, select it, choose the move object mode as seen below, then click and drag in the simulation. 

Make yourself a little path.

![img/pathMade.jpg]

In the `Path edition` window check mark the box `Path is closed`. This will turn your path into a loop. Now select all the points you've made and return to the `Path edition` window and change the `Bezier interpolation factor` 1 and 2 to `.99` and then hit `Apply to selection`. Take note of the changes. The corners should be more curvy. 

Close the `Path edition` window, chosing to save it in the dialog box that pops up. 

![img/moveObject.jpg]

