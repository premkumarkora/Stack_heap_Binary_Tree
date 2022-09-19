# Stack_heap_Binary_Tree

<b>Stack</B>

Stack is a simple data structure and it stores elements like pile of plates. Operation in stack is done on top of stack meaning, we can perform insertion and deletion on top pointer of stack.

Consider a pile of 10 numbered plates with 1 at the bottom and 10 at the top, to remove plate 5, we need to remove 10, 9, 8, 7, 6 then 5 in that order, to perform deletion. This procedure of deletion or accessing an element is called Last In First Out (LIFO). The things that comes last, will be removed first.

A stack is a linear data structure that stores items in a Last-In/First-Out (LIFO) or First-In/Last-Out (FILO) manner. In stack, a new element is added at one end and an element is removed from that end only. The insert and delete operations are often called push and pop.

Basic operations in Stack
Push — Adding element at the top of the stack

Pop — Removing the top element from stack

isEmpty — Check if stack is empty or not

size() – Returns the size of the stack

top() / peek() – Returns a reference to the topmost element of the stack

isFull — Check if stack is full or not

<b>Implementation using collections.deque:</b>

Python stack can be implemented using the deque class from the collections module. Deque is preferred over the list in the cases where we need quicker append and pop operations from both the ends of the container, as deque provides an O(1) time complexity for append and pop operations as compared to list which provides O(n) time complexity.

<b>queue module</b>

Queue module also has a LIFO Queue, which is basically a Stack. Data is inserted into Queue using the put() function and get() takes data out from the Queue.

There are various functions available in this module:

maxsize – Number of items allowed in the queue.

empty() – Return True if the queue is empty, False otherwise.

full() – Return True if there are maxsize items in the queue. If the queue was initialized with maxsize=0 (the default), then full() never returns True.

get() – Remove and return an item from the queue. If the queue is empty, wait until an item is available.

get_nowait() – Return an item if one is immediately available, else raise QueueEmpty.

put(item) – Put an item into the queue. If the queue is full, wait until a free slot is available before adding the item.

put_nowait(item) – Put an item into the queue without blocking. If no free slot is immediately available, raise QueueFull.

qsize() – Return the number of items in the queue.
