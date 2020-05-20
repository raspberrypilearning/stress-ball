## Squish it
Now you can add code to make the stress ball look like it's being squished when you click or tap on it. 

--- task ---

Click on the **Code** tab

![screenshot](images/balls-code.png)

--- /task ---

Now you are in the Code Editor.

--- task ---
Click on the Ball sprite, and then drag a `when this sprite clicked` block, from `Events` into the code area on the right:

```blocks3
when this sprite clicked
```

--- /task ---

--- task ---
Drag a `set color effect to` block underneath the `when this sprite clicked` block and make sure it 'snaps' into place: 

```blocks3
when this sprite clicked
+set [color v] effect to (0)
```

The colour of each block tells you where to find it. 

--- /task ---

--- task ---
Click on `color` and change it to `whirl`:

```blocks3
when this sprite clicked
+set [whirl v] effect to (0)
```

--- /task ---

--- task ---
Click in the 0 box and change the value to 100 (lots of whirl)

```blocks3
when this sprite clicked
+set [whirl v] effect to (0)
```
--- /task ---

--- task ---
Add a 'play sound until done' block.

```blocks3
when this sprite clicked
set [whirl v] effect to (0)
+play sound [Pop v] until done
```

--- /task ---

--- task ---
Click on the arrow and choose the Boing sound instead of Pop.

```blocks3
when this sprite clicked
set [whirl v] effect to (0)
+play sound [Boing v] until done
```
--- /task ---

--- task ---
Click on your stress ball to see it shrink and get whirled and then play the sound.

![screenshot](images/balls-effect.png)

--- /task ---

--- task ---
Now add code to return your ball to normal.

```blocks3
when this sprite clicked
set [whirl v] effect to (0)
play sound [Boing v] until done
+ clear graphic effects
```
--- /task ---

--- task ---
Check carefully that your code looks exactly like this:

```blocks3
when this sprite clicked
set [whirl v] effect to (0)
play sound [Boing v] until done
clear graphic effects
--- /task ---

--- task ---
Click on your sprite to try it out. 
--- /task ---

