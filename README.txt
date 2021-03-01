Ian Chen, Gabriel Hardy

We created some helper functions to make everything more readable.
To avoid conflicts, we made sure there was no left recursion or common left factors.

We were unable to resolve 4 of our conflicts, which causes our program to fail to compile. They are all shift/reduce. The program can be compiled by changing 'expect -3' 'expect -4' in the Makefile script.
