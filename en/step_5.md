## Choose your own sound effect

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Add a better sound effect to your stress ball.
</div>
<div>
![](images/sound-effect.png){:width="300px"}
</div>
</div>


--- task ---
Click on the **Sounds** tab.

![screenshot](images/balls-sound-tab.png){:width="500px"}

--- /task ---

--- task ---
Click on **Choose a Sound**.

![screenshot](images/balls-choose-sound.png){:width="500px"}

--- /task ---

--- task ---
Click on the **Wacky** category.

![screenshot](images/balls-wacky.png){:width="500px"}

--- /task ---

--- task ---
Click on the **Play** button for the **Squeaky Toy** sound to hear it. 

![screenshot](images/balls-play-button.png){:width="500px"}

Then, click on **Squeaky Toy** to add the sound to the **Ball** sprite. Now, you can use this sound in your code.

--- /task ---

--- no-print ---

![screenshot](images/balls-step6.gif) 

--- /no-print ---

--- task ---
Click on the **Code** tab to return to the Code area. 

Click on `Boing`{:class="block3sound"} in the `play sound Boing until done`{:class="block3sound"} block and change it to `Squeaky Toy`{:class="block3sound"}.

![screenshot](images/balls-squeakytoy.png){:width="300px"}

Your code should look like this:

```blocks3
when this sprite clicked
change size by (-50)
set [whirl v] effect to (100)
+play sound [Squeaky Toy v] until done
clear graphic effects
set size to (200)%
```
--- /task ---

--- task ---
Click on your stress ball again to try out the new sound effect. 
--- /task ---

--- save ---
