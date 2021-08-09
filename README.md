# COMP313_Assignment_1

## A simple 2D side scroller.

### What is the main action in the game?

The main action of this game is movement and collisions.
I have created a jumping character with a 'shift-hold' function which changes the speed and animation of the character.
I have also produced an npc that will walk to the character when in range, and attack when close up to the player.

### What was the hardest part of the game to get working in Unreal

The hardest part, that took the longest to get working was the animation and interaction of the NPC hitting the player.
It took some trial and error to get the animation to play once, and time it correctly with the impact.
But similarly, another difficult part of the game was getting the heart counter to work correctly.

### What is the most interesting part of the game

I feel the most interesting thing about this game is the interaction between the NPC and the player. Most notibly the attack swing, and whether it hits the player or not.
I check to see if the player is within attack range, and then start the animation.
If the player is still inside the range when the attack is supposed to land, then the player takes damage.
If the player is quick, and moves outside of the range while the NPC is swinging, there is a 'miss' sound that plays and the player takes no damage.
