# Useful Commands:

## Motion
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/motion-1.![alt          | This block moves the sprite’s X position by the specified amount         |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/motion-2.![alt              | This block moves the sprite’s Y position by the specified amount        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/motion-3.![alt              | This block changes the Rotation Style of the sprite.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/motion-4.![alt              | This block checks if the sprite is touching the edge of the screen with the move steps block. If it is, the sprite will point in a direction opposite to the direction from which it is coming. It uses a line perpendicular to the edge to determine the reflection angle.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/motion-5.![alt              | The block sets the sprite's X and Y position to the specified amounts. This block is used whenever a sprite needs to go from one spot to another        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/motion-6.![alt              | This block holds the sprite's X position        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/motion-7.![alt              | This block holds the sprite's Y position        |

## Looks
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/looks-1.![alt          | If the sprite is hidden, it will show the sprite. If the sprite is already showing, nothing will change.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/looks-2.![alt          | If the sprite is shown, it will hide the sprite. If the sprite is already hidden, nothing happens.         |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/looks-3.![alt          | This block changes its sprite's costume to a specified one.         |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/looks-4.![alt          | This block changes the Stage’s backdrop to the specified one.        |

## Sound
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/sound.![alt          | This block will play the specified sound, pausing until the sound has finished playing        |

## Events
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/Event-1.![alt          | Scripts will be activated once this block has been clicked. Without this block, the only way a project could run would be that it would sense the pressing of a key or clicking a sprite. More simply, this block starts the project.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/Event-2.![alt          | This block will activate the code logic placed under this when the specified key is pressed.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/Event-3.![alt          | Scripts that begin with this block will be invoked once the specified broadcast has been sent by a calling script.        |

## Control
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/control-1.![alt          | Code logic held inside this block will be in a loop and the loop never ends (unless the stop sign is clicked, the Stop All block is activated, or the stop script block is activated within the loop).        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/control-2.![alt          | This block pauses its script for the specified number of seconds. The wait can also be a decimal number.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/control-3.![alt          | This block will check its Boolean condition, and, if the condition is true, the logic held inside it will run, and then the script involved will continue. If the condition is false, the code inside the block will be ignored and the script will move.        |


## Sensing
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/sensing.![alt          | This block checks if the sprite is touching the mouse-pointer, edge, or another sprite. If the sprite is touching the selected object, the block returns true, and returns false if it is not.        |

## Operators
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/op-1.![alt          | This block joins two Boolean blocks so any one of them can be true to return true. If at least one of them is true, the block returns true; if neither of them are true, it returns false.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/op-2.![alt          | This block picks a random number ranging from the first given number to the second, including both endpoints. If both numbers have no decimals, it will report a whole number. For example, if a 1 and a 3 were inputted, the block could return a 1, 2 or 3. If one of the numbers has a decimal point, even .0, it reports a number with a decimal. For example, if 0.1 and 0.14 were given, the output will be 0.1, 0.11, 0.12, 0.13, or 0.14.        |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/op-3.![alt          | This block checks if the first value is less than the second value. If it is less, the block returns true, else, it returns false.        |

## Variables
| Block     | Function |
| ---      | ---       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/var-1.![alt          |  Set the value of the selected variable to the given input.       |
|        ![alt tag](https://github.com/NetApp-YWIT/ywit_2020_debugging_workshop/blob/main/Images/var2.![alt          |  Add / remove the given value to/from the selected variable       |
