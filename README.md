# in-class-activities
## Devlogs
### W1
"Hello World!"
Today I have learned how to kind of navigate Unity and how to push trough Github. 
I now know how to get all of the homework turned in and I've set myself up to be able to use the class Github. 
Right now I am writing my first Devlog, so that means I know how write these now. 
I plan to commit this first mini project after I'm done writing this. 
I moved the cat from red to green, made it able to move faster and turn faster. 
The cat can move at all because I assigned the movement animation. 

### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.

### W3
Imagine we need to design a method to perform the following function. 
What would you make the parameters (input) and return type (output) of this method?
Tables 7-13
You’re building a visual novel, and you’re writing a method named GetResponse that gives you a character’s 
text response to a player’s dialogue choice based on the player’s current friendship level with the character 
and a flag that tells you whether or not the player knows the character’s secret.
The inputs would be the friendship level and if the player knows the secret. The outputs would be the diologue choice and if the flag is waived. 
The output would be a sting and a boolean. 

Metaphor:
The classes are like the frames that do nothing by themselves. The Component is like the lenses that tint, perscript, or block out blue light. 
The frames are useless without the lenses, but the lenses need the frames to be held in place. 

The balls get super bright because the color is always multiplied up and doesn't loop or darken at any point. 

### W4
Table #12
Line 17: private bool _isGrounded = true; 
	Creates a private boolean within the class and sets it to true. 
Line 28: if (Input.GetKeyDown(KeyCode.Space) && _isGrounded)
Takes the parameters of if the space key is held down and if the private boolean is true to then run the code after/ jump without double jump
Line 32: _isGrounded = false;
This is within the if statement and makes it so that when the space key is pressed, then the player is no longer grounded according to the boolean

I added RigidBodies to the Cat and the SoccerBall and used the cube collision to add a IsTrigger on the goal. 
My main problem with this game was confusion with the Trigger and Collision methods and where to use them. Once I figured that out, I was good. 

### W5
What is the difference between using the gameObject as collider like in the notes versus using other like in the Minigame 4?
Ans: It is just another name to call upon in the Collider group. 
Plan:
Copy the CatW5
Figure out what to change
Delete what is inside and make update() to start()
Make deer walk 
Figure out nav mesh
Learn how to get the components in Inspector
Look for where set destination goes


## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 