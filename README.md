# Stack-using-Array
The Array implementation of stacks involves allocation of fixed size array in the memory.Both stack operations (push and pop) are made on this array with a constant check being made to ensure that the array does not go out of bounds.


Push Operation:- The Push operation involves checking whether or not the stack pointer is pointing at the upper bound of the array. If it is not,the stack pointer is incremented by 1 and the new item is pushed (inserted) at the top of the stack


Algorithm to implement push operation under array representation of stacks:-

Step 1:Start

Step 2:If top=max-1 go to Step 3 else go to Step 4

Step 3:Display message "Stack full" and exit

Step 4:top=top+1

Step 5:stack[top]=element

Step 6:Stop


Pop Operation:- The pop operation involves checking whether or not the stack pointer is already pointing at NULL(empty stack). If it is not, the item that is being currently pointed is popped(removed) from the stack (array) and the stack pointer is decremented by 1.


Algorithm to implement pop operation under array representation of stacks:-

Step 1:Start

Step 2:If top=-1 go to Step 3 else go to Step 4

Step 3:Display message "Stack Empty" and Exit

Step 4:Return stack[top] and set top=top-1

Step 5:Stop


This program uses the Push and Pop algorithms for realizing common stack operations.

This program code shows storage of an integer type element into the stack. However, we may store other built-in or user defined type elements in the stack as per our own requirements.

For application of stack refer to the following website:-
https://www.javatpoint.com/applications-of-stack-in-data-structure
