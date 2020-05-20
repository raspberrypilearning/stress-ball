## Shrink it

Now you're going to make your stress ball shrink as well as squish when you click on it.

--- task ---
Drag a `change size by`{:class="block3looks"} block under your `when this sprite clicked`{:class="block3events"}. A space will open up for the block and it will snap into place. 

![screenshot](images/balls-change-size-snap.png)

Your code should look like this:
```blocks3
when this sprite clicked
+change size by (10)
set [whirl v] effect to (100)
play sound [Boing v] until done
clear graphic effects
```
--- /task ---

--- task ---
You want the stress ball to get smaller when you click it so change the number in the `change size by`{:class="block3looks"} block from `10` to `-50`. Choosing a negative number will make the sprite shrink.

```blocks3
when this sprite clicked
+change size by (-50)
set [whirl v] effect to (100)
play sound [Boing v] until done
clear graphic effects
```
--- /task ---

--- task ---
Now add a `set size to`{:class="block3looks"} block to the bottom of your code and set your sprite back to **200**%. 

```blocks3
when this sprite clicked
change size by (-50)
set [whirl v] effect to (100)
play sound [Boing v] until done
clear graphic effects
+set size to (200)
```

--- /task ---

--- task ---
Click on your stress ball to try it out. 

--- /task ---
