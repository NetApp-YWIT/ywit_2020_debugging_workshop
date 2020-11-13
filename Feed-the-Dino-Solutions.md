# Solutions to Feed the Dino Game

## How the game should work:

1.	The arrow keys on the keyboard (left and right) should move Dino (Sprite 1) left and right.  

2.	Right arrow should move Dino to the right.

3.	Left arrow should move Dino to the left.

4.	Bananas (Sprite 2) , Apples (Sprite 3) and Rocks (Sprite 4) should be falling from top randomly.

5.	Feed the Dino with bananas and apples, and save it from the rocks.

6.	When the Dino is fed a banana, the score should increase by 2.

7.	When the Dino is fed an apple, the score should increase by 1.

8.	When the Dino is hit by a rock, score should decrease by 2.

9.	A timer should start at 30 seconds and subtract 1 second until the timer is 0.

10.	Game should end in 30 seconds.

11.	All the sprites should be hidden on game over.

12.	The goal of the game is to score maximum in 30 seconds.



## List of Bugs:

1)	Dino is not moving left

2)	When the Dino is fed banana, the Score is not being increased

3)	When the rocks fall on the Dino, the Dino’s costume is not being changed

4)	Timer is incrementing instead of decrementing

5)	Apples are not visible

6)	Apples are not falling from top. 

7)	Once the above bug is fixed, apples are always falling in one place

8)	When the timer reaches zero, it does not show “game over”

9)	There is no pop sound when the Dino is fed bananas 

10)	Even after the Game is over, the bananas are still visible


## Solutions

### 1.	Dino isn't moving left:

Solution:

Go to Dino Sprite and add the code to change the x coordinate of the sprite to change by -40 when left arrow key is pressed. Motion blocks will move your sprites in different ways (position, rotatio, etc.,)

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-1.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-1.png)         |



### 2.	The score does not change on feeding a banana to the Dino

Solution:

Go to banana sprite and correct the condition specified in sensing block. The outer block controls the inner blocks. If the condition in outer ‘if’ control block is not met, then the inner blocks will not get executed.


| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-2.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-2.png)         |



### 3.	The Dino’s costume is not changed when hit by a rock.

Solution:

Go to Rock sprite and add the code to change the costume of Dino when it touches rock. The looks blocks help you to change the costumes and backdrops for your sprites and stages.

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-3.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-3.png)         |


### 4.	Timer is incrementing instead of decrementing

Solution:

Go to Background and check if time is decrementing every second. It says, ‘Change timer by 1’, it should be ‘Change timer by -1’. Variables blocks are helpful for keeping track of all the information your sprite or Stage needs to know.

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-4.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-4.png)         |


### 5.	Apples are not visible

Solution:

Verify in the apple Sprite if it is Shown when the green flag is clicked. The looks blocks also tell your sprite to show itself or hide—they can even tell your sprite to say something!

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-5.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-5.png)         |


### 6.	Apples are not falling from the top

Solution:

A good way to debug this is to look at the code for Banana or Rock sprite which works correctly. Compare the code scripts and try to see if you can figure out the issue. The difference between Banana sprite and Apple sprite is that Banana Sprite uses a forever loop to make the ‘change by’ instruction decrement y by 7 in a loop.

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-6.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-6.png)         |


### 7.	The Apples are always falling in one place.
 
Solution:

Go to Apple sprite and verify if rand function is added into x coordinate. The motion blocks will move your sprites in different ways.

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-7.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-7.png)         |


### 8.	When the timer reaches zero, it does not show “game over”

Solution:

Go to the stage and add the code to change the backdrop when timer reaches 0. The looks blocks help you to change the costumes and backdrops for your sprites and stages.

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-8.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-8.png)         |


### 9.	There is no pop sound when the Dino is fed apple or banana.

Solution: 

In the bugged code logic, it says ‘if touching bananas and touching apple’. This means there is a pop sound only when Dino is fed both apple and banana at the same time. The boolean logic being used here is incorrect. It should be ‘if touching bananas or touching apple’.

| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-9.png) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-9.png)         |



### 10.	Even after the Game is over, the bananas are still visible

Solution:

Check in bananas sprite if it hides when the sprite receives Game over message from The background. The looks blocks also tell your sprite to show itself or hide—they can even tell your sprite to say something!


| Buugged Code     | Debugged Code |
| ---      | ---       |
| ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/bug-10.PNG) | ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/debug-10.PNG)         |















