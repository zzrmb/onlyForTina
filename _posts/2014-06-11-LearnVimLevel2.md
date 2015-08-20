---
layout: default
title: Learn Vim Level 2
---

## Level 2 Feel Better 

###INSERT
* a   append text after the cursor
* o   begin a new line after the cursor
* O   begin a new line before the curesor
* cw  change word 

###MOVE
* 0   move to the head of this line
* $   move to the end of this line
* e   move to next word
* ^   move to the first non-blank character of this line 
* g_  move to the last non-blank character of this line

###SEARCH
* /pattern   Use pattern to search forward, use n for next 
* ?pattern   Use pattern to search backward, use n for next
* If use * on one word, vim will search it for you.
* Need to learn more about pattern.

###VISUAL MODE
* Use v to start visual mode 
1 x or d   delete
2 y   copy
3 r   replace
4 u   to lower case
5 U   to upper case 


###COPY PASTE DELETE
* y   copy from current position to your next move
* yy  copy this line, same with ddp
* y$  copy from current position to end of this line
* p   paste
* d   delete from current position to your next move

###FILE OPERATION
* :e path_to_file    open one file
* :w    write 
* :saveas path_to_file     save to one location
* :x or :wq or ZZ   write and exit
* :q!   exit without write
* :bn   change to next file
