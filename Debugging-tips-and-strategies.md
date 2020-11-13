# Debugging tricks and Strategies

## One at a time:

Always try to debug one instruction at a time. This way, you can know if your change worked. If you try changing 15 or more instructions and it works, you will not know what worked. So, you will have to retest again and again.

## Corner out the issue:

Identify which part if the program has the issue. Is it an issue with the sprite or Script or background? Trouble shooting becomes easier after this. If you do this step wrong, you will lose lot of time looking in the wrong place.

## Compare:

Try to compare the bugged code with a similar working module. Try to verify if there are any blocks missing or any variables not set properly or if the sequence of the instructions match etc.,

## Always Divide and Conquer:

Split your program into modules. Check if there is any issue with each module. If you observe any issue with a module, debug it. Merge it with other modules, check if they are working fine together. 

## Blocks inside Blocks inside Blocks:

Always check for the structure of the program. There will be these nested blocks, where a block has another block inside it. Check each condition the program must meet to get inside the inner block. Are these conditions set properly? Or these blocks nested correctly? Is there a forever block missing? 

## Ask Questions:

Never be afraid to ask questions. If you are stuck somewhere, ask your friends or parents to help you further.

## Never Give Up:

Yes, Debugging can be frustrating and time consuming, but, you will catch the Bug in the end. Don’t give up


![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/tips.png)


## The Golden Rule
Don’t ever be afraid to ask questions. Programming is hard and everyone needs help. Ask questions if you need help with anything! For any questions after the session, please send your questions to ng-ywit-questions@netapp.com with the workshop title "Catch Bugs With Us" in the email subject line. All the solutions from the workshop will be made available in this GitHub repository shortly after the conclusion of the session.
