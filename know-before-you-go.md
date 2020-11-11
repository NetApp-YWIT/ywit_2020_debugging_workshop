# Scratch Workshop: Let’s Sharpen Our Claws!

## What is Scratch?

A Scratch project can be any number of things—a cartoon, a game, a puzzle. A project is made up of four primary components:

I.	Scripts – You write them and they control everything! 

II.	The Stage – It is the environment in which everything takes place! You can control this environment with scripts.

III.	Sprites – Any number of sprites will populate your project and can perform all kinds of roles; your scripts will tell them what to do!

IV.	Backdrops/Costumes – these are the various backgrounds and appearances your Stage and Sprites will use. The Stage and Sprites can have any number of different backdrops/costumes and change between them.

You can think of Scratch like a play. What are some components of a play?

I.	The Script

II.	The Stage

III.	The Actors

IV.	The Costumes

### I. The Script
 At the center of any good play is well-written script (of course, Hollywood may disagree 😋). The scripts tell the stage to change scenes and the actor what to do. 
They perform the same function in Scratch: Scripts control the Stage and all the Sprites in a Scratch project. Here’s a quick rundown of a Scratch Script:

•	A script belongs to a sprite or a stage. A sprite or a stage can hold any number of scripts.

•	A script begins with an ‘Event’ block. The event block represents something that tells the holder of that script to begin following that script’s instructions.

•	A script is made up of blocks which each represent an instruction. An instruction might tell the stage to change its backdrop or tell a sprite to scooch over to the left.

#### Try it for yourself:
1.	Give the Sprite named ‘Player’ a new script that tells it to say ‘Hello’ when the space bar is pressed:

  I.	Start the script with a ‘when space key is pressed’ block from the ‘Event’ section of instructions. Simply drag it into the ‘Player’ sprite’s workspace.

  II.	Grab the block ‘say hello! For 2 seconds’ from the ‘Looks’ section of instructions and drag it underneath the ‘when space key is pressed’ until the two blocks click together.

2.	Start the project by pressing the green flag at the top of the project. Now press the space bar—your ‘Player’ should greet you with a hearty ‘Hello!’

### II. The Stage
Think about the one thing that’s always fixed in a play. The actors will enter and exit scenes and backdrops transform—but the stage is always there. In many ways, it serves to coordinate and frame a play.

The same concept is present in Scratch, and it is also called a Stage. Here’s a quick rundown of a Scratch Stage:

•	There can only be ¬ONE stage in Scratch.

•	A stage can follow scripts. You can tell the stage to play music, send messages to the sprites, etc…

•	A stage can change backdrops. Think of it like when a play transitions from a night scene to a day scene. The stage stays the same, but the stage background might brighten and a new set might be brought in.

•	A stage can have variables—a variable is like a reminder of a value. You might not remember the value, but Scratch can for you! 

#### Try it for yourself:
1.	Change the backdrop of the demo stage to something else
2.	Have a sound play when the demo Scratch project is started

### III. Actors
You can’t have a play without actors! In Scratch, the actors are called Sprites and they can perform any number of functions. Here’s a quick rundown:

•	You can have as many Sprites as you want in a project! Go nuts!

•	A Sprite—just like an actor—follows scripts. They can follow any number of instructions—and its up to you to make those instructions.

•	A Sprite can also have variables. They can have two kind of variables: 1) A GLOBAL variable is a reminder that EVERYONE can see (including the stage and other 
sprites); and 2) A PERSONAL variable is a reminder ONLY that Sprite can see.

•	A Sprite moves around the stage using X, Y coordinates. Be sure to keep track of where each sprite is using a personal variable—you can keep track of them easily this way!

•	Sprites can either being SHOWING or HIDDEN. Your scripts will tell them when they should show themselves or hide!

•	A Sprite—just like an actor—wears a costume. A sprite can have any number of costumes (and can look like just about anything). You can tell a sprite in a script to change its costume.


#### Try it for yourself:
1.	Create a new sprite and add it to the demo project
2.	Choose a costume for the sprite
3.	Have that sprite start in the middle of the stage when the Scratch project is started:

  i.	Give the Sprite a script that sets a Personal variable name ‘x’ to 0 and another Personal variable named ‘y’ to 0 when the Scratch project starts.

  ii.	From the ‘Motion’ blocks, grab a ‘go to’ block and append it to the script you just made. 

  iii.	In the ‘x’ bubble of the ‘go to’ block, put your sprite’s ‘x’ variable. In the ‘y’, bubble of the block, put your sprite’s ‘y’ variable. 

### IV. The Costumes
You may have noticed this already--but Sprites and the Stage can have their appearances altered with costumes (for Sprites) and backdrops (for the Stage). Here’s a brief rundown:

•	You can select from pre-made costumes/backdrops or draw your own. You can even upload images to your project which you can use in your costumes/backdrops

•	The ‘Look’ section of instructions has instruction blocks that allow you to change your sprite’s costume using a script

•	Obviously, costumes can make your sprites look super swell—but they can also be used to make your Sprites appear to move! Take a look at the ‘Player’ sprite and try to figure out how it appears to move.

So, get movin’ and spruce up your Sprites with spiffy costumes! Make your Stage pop with bangin’ backdrops!

#### Try it for yourself:
1.	Give the sprite you just created a new costume.
2.	Look at the ‘Player’ sprite script called ‘Move’. Look at the costumes the ‘Player’ sprite has equipped. Try to figure out how its moving (hint: its just like a flip book you might draw when you were younger)


## Finding the Right Block
Scratch gives you a lot of blocks to use for your scripts. There are lots of blocks and it is easy to get lost or confused. The blocks are organized by category to help you find the right tool for the job. You will mix and match these blocks in your script.

### Motion
•	These blocks will move your sprites in different ways (position, rotation, etc.) A Stage doesn’t move so it cannot use these.
Looks
•	The blocks help you to change the costumes and backdrops for your sprites and stages.

•	These blocks also tell your sprite to show itself or hide—they can even tell your sprite to say something!

### Sounds
•	These blocks help you control the sound that comes from your sprites or backdrop

### Events
•	These blocks in this section are typically used at the start of a script. These blocks listen for specific events to occur (like pressing a key, hearing a message, or when the green start button is pressed)—when they do, the script is started, and the sprite or Stage will begin following the instructions listed in the script.

•	Some blocks in this section broadcast a message that other scripts can hear. You can use these blocks to have your sprites and Stage talk to one another. For example, when your sprite reaches the end of the screen, it can send a message to your Stage to change the backdrop to a new scene.

### Control
•	These blocks are the workhorses of your script. While they don’t do anything on their own, they are used in combination with Sensing and Operator blocks to guide Motion, Looks, Sound, and Event blocks. Maybe you wanted your sprite move 10 times and then stop. You could use a Control block (the repeat block) containing a Motion block (specifically the move block) to accomplish this.

### Sensing
•	These are some fancy blocks—typically used for helping out your Control blocks. They let the Control block know if a sprite is touching another sprite, if a key was pressed, or if your sprite is touching the edge of the Stage.
•	Some of these blocks aren’t just for helping Control blocks either. Some can ask for input from a player or keep a timer. Neato!

### Operators
•	Operators help your Control blocks make decisions. What if you wanted a sprite to win a game only if it had collected 10 points? You could use a Control block (the if block) to check IF a sprite’s point total was equal to 10.

### Variables
•	Variables are helpful for keeping track of all the information your sprite or Stage needs to know. You can create any number of variables and use them assist Operator and Control blocks in coming to a decision.
