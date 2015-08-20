---
layout: default
title: Learn Vim Level 3
---

## Level 3 Better, Stronger and Faster 

###HOW TO REPEAT
* .   repeat your last change
* N<command>  repeat the command for N times, for example 2dd means delete two lines 

###MOVE FASTER
* NG  move to Nth line
* :N  move to Nth line
* gg  move to the first line
* G   move to the last line

###MOVE BY WORD
* w   move to next word head
* e   move to next word end
* E or W  move to next word seperated by blank

###MOVE BY CURRENT CURSOR
* Use * to move to next current cursor word
* Use # to move to last current cursor word
* Use % to move to next brace, including (,{,[,),},]


###USE CURSOR MOVE IN YOUR COMMAND
* many command has this schema: <start position><command><end position>
* for example:  0y$ means 
1. 0 move to the head
2. y start copy from current position
3. $ to the end of this line

* you can also type:  y$  then you will copy from current position to the end of this line
* so  dG  will delete all the characters from current position


