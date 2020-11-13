# Maze Game

## Scratch link for game with Bugs

![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/maze.png)



## How the game should work:

Use the arrow keys to move the cat, get keys to open the yellow doors and catch the mouse to win the game. The cat cannot walk through the blue walls and would meow if it hits the wall. The number of the keys on the left upper corner would record how many keys have been acquired and not yet used. Each key can only be used for one door. 



## Check List: 

(1) The Cat, three keys, the mouse, the blue maze and three yellow doors should show after green flag is clicked. 
 
(2) Pressing up arrow key can move cat upward when it is not blocked by blue wall or yellow door. 

(3) Pressing down arrow key can move cat downward when it is not blocked by blue wall or yellow door. 

(4) Pressing left arrow key can move cat to the left when it is not blocked by blue wall or yellow door. 

(5) Pressing right arrow key can move cat to the right when it is not blocked by blue wall or yellow door. 

(6) The cat would change costume when arrow key is pressed. 

(7) The cat would meow when hitting the blue wall and will be bounced back. 

(8) The cat would meow when hitting the yellow gate and will be bounced back. 

(9) when the cat touches a key, the key would disappear, the keys count on the left upper corner would increase by 1, and the “A Guitar” sound would play. 

(10) When the cat touches a yellow door with at least one key, the yellow door would disappear, the keys count on the left upper corner would decrease by 1, and the “Big Boing” sound would play.  

(11) When the cat touches the mouse, the mouse would say “You win!” for 4 seconds then disappear, the “Cheer” sound would play. 



## List of Bugs in the game: 

Bug 1: cannot move (missing forever loop)

Bug 2: Cannot move down (missing if key down arrow statement)

Bug 3: Can go through walls when moving up, can get stuck on the upper boundary

Bug 4: Can go through wall when moving to the right, can get stuck in the right most part

Bug 5: Cannot open the small yellow door(the one locked two keys), even when have key

Bug 6: Open small yellow door does not decrease key number

Bug 7: Cannot open the left big yellow gate when holding two keys. 

Bug 8: Sometimes cat does not meow when touch the wall or door.

Bug 9: Cat leg does not move when moving up.

Bug 10: The mouse does not show again once got caught, cannot play the game again.


## Finished with your debugging activity?
•	Congratulations!! You have successfully debugged Maze game! Way to go – you are officially a developer now. Believe me, this is how coding/developing works.

•   You can add more intentional bugs into the project and challenge your friends to debug it.


## The Golden Rule
Don’t ever be afraid to ask questions. Programming is hard and everyone needs help. Ask questions if you need help with anything! For any questions after the session, please send your questions to ng-ywit-questions@netapp.com with the workshop title "Catch Bugs With Us" in the email subject line. All the solutions from the workshop will be made available in this GitHub repository shortly after the conclusion of the session.
