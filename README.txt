Ian Chen, Gabriel Hardy

We created some helper functions to make everything more readable.
To avoid conflicts, we made sure there was no left recursion or common left factors.

We were unable to resolve 10 of our conflicts, which causes our program to fail to compile. 3 of the conflicts are reduce/reduce and 7 are shift/reduce. The program can be compiled by changing 'expect -3' 'expect -10' in the Makefile script.
