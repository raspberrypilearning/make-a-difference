## Make a sprite to move

Now it's time to get your first sprite moving. Let's start with one sprite and then add more. 

Each sprite will `move`{:class="block3motion"} within a `forever`{:class="block3control"} loop so that the sprite will move forever unless it is clicked.

--- task ---
This **Yellow Balloon** sprite moves up and down the stage, changing direction when it hits the top, sides or bottom. 

--- no-print ---
![Animated gif showing path of sprite](images/moving-up-down.gif){:width="400px"}
--- /no-print ---

--- print-only ---
![Image annotated with path of sprite](images/moving-up-down.png){:width="400px"}
--- /print-only ---

Here's the code it uses:

```blocks3
when flag clicked
set size to (80)%
clear graphic effects :: looks
set [ghost v] effect to (15)
+ point in direction (0)
show
forever
move (5) steps
+ if on edge, bounce
end
```

Let's look at the bottom part of the script to understand how it makes the sprite move. We'll look at the top part afterwards!

Choosing `0` in the `point in direction`{:class="block3motion"} block makes the sprite point upwards so the `move`{:class="block3motion"} block will make the sprite move up to the top of the Stage area. If the sprite touches the top of the Stage it will flip direction and start moving down towards the bottom of the stage and so on. The balloon sometimes bounces off the sides of the Stage area.

--- /task ---

--- task ---

Think about how you want **your** sprite to move. For example, you might say "I want my sprite to move up and down the stage really slowly," or "I want my sprite to be really small and move quickly in a diagonal line."

--- /task ---

--- task ---

Select your first sprite and click on the **Code** tab. 

![Code tab selected](images/code-tab.png)

--- /task ---

--- task ---

Add code to make your sprite move around the stage in a forever loop, bouncing off the edges of the stage. 

--- no-print ---

Click on the green flag to investigated how experience varying sprite movement. Each sprite uses different `Motion`{:class="block3motion"} blocks. Click `SEE INSIDE`{:class="block3motion"} the project and then click the **Code** tab for each sprite to see how a particular sprite movement can be achieved:
<div class="scratch-preview">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/BLAH/?autostart=false" frameborder="0"></iframe>
</div>

--- /no-print ---

**Add me in: generic-scratch-if-on-edge-bounce **


--- /task ---

--- task ---

Change the speed and direction of your sprite until you get the effect you want. It might take a few experiments to get it right. That's ok.

--- /task ---

--- task ---

You may want to change the way your sprite's costume rotates when it moves to stop it going upside down.

**Add me in: scratch-rotate-costume **

--- /task ---

**Tip:** It's easier to identify issues if you make one change at a time and then run your program. 

--- task ---

Remember to keep running your project to test it. Is the program working as you had planned?

--- /task ---

--- save ---