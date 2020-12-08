## Squash it
Now, you can add code to make the stress ball look like it is being squashed when you click or tap on it. 

--- no-print ---

--- task ---

Watch this short video, which shows what to do next.

![screenshot](images/balls-step4.gif) 

--- /task ---

--- /no-print ---

Now, follow the instructions for each task below.

--- task ---

Click on the **Code** tab.

![screenshot](images/balls-code.png){:width="500px"}

Now, you are in the **Code area**.

--- /task ---

--- task ---
From the `Events`{:class="block3events"} blocks menu, drag a `when this sprite clicked`{:class="block3events"} block into the Code area on the right-hand side:

![screenshot](images/balls-when-this-sprite-clicked.png){:width="500px"}

```blocks3
when this sprite clicked
```

--- /task ---

--- task ---
From the `Looks`{:class="block3looks"} blocks menu, drag a `set color effect to`{:class="block3looks"} block underneath the `when this sprite clicked`{:class="block3events"} block and make sure that they connect together:

```blocks3
when this sprite clicked
+set [color v] effect to (0)
```

Notice that the colour of each block tells you where you can find it. 

--- /task ---

--- task ---
Click on `color`{:class="block3looks"} and change it to `whirl`{:class="block3looks"}.

![screenshot](images/balls-color-whirl.png){:width="300px"}

Your code should look like this:

```blocks3
when this sprite clicked
+set [whirl v] effect to (0)
```

--- /task ---

--- task ---
Change the value from `0` to `100`:

```blocks3
when this sprite clicked
+set [whirl v] effect to (100)
```

This will create lots of whirl!

--- /task ---

--- task ---
Add a `play sound Pop until done`{:class="block3sound"} block:

```blocks3
when this sprite clicked
set [whirl v] effect to (100)
+play sound [Pop v] until done
```
--- /task ---

--- task ---
Click on `Pop`{:class="block3sound"} and change it to `Boing`{:class="block3sound"}:

![screenshot](images/balls-pop-boing.png){:width="300px"}

```blocks3
when this sprite clicked
set [whirl v] effect to (100)
+play sound [Boing v] until done
```
--- /task ---

--- task ---
Click on your stress ball to see it whirl and then play the sound.

![screenshot](images/balls-effect.png){:width="150px"}

--- /task ---

--- task ---
Click on `Looks`{:class="block3looks"}, then click on the `clear graphic effects`{:class="block3looks"} block in the Blocks menu to remove the whirl effect. You might need to scroll down to find the block.

![screenshot](images/balls-clear-graphic-effects.png){:width="300px"}
--- /task ---

--- task ---
Now, add a `clear graphic effects`{:class="block3looks"} block to the bottom of your code so that the ball always returns to its original state after it has been squashed: 

```blocks3
when this sprite clicked
set [whirl v] effect to (100)
play sound [Boing v] until done
+ clear graphic effects
```
--- /task ---

--- task ---
Check carefully that your code looks exactly like this:

```blocks3
when this sprite clicked
set [whirl v] effect to (100)
play sound [Boing v] until done
clear graphic effects
```

--- /task ---

--- task ---
Click on your sprite to try it out. Try it again. Then, try it again!
--- /task ---

__Tip:__ If you are logged in to Scratch then your project will save automatically, but you can also use **File** then **Save now**. If you do not have an account or you are working offline, remember to use **File** then **Save** when you make an important change. 

--- save ---
