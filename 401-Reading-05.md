
Reading Note Linked lists

Linked lists explained using WHAT IT IS? WHY USE IT? AND HOW TO USE IT?
What is a Linked List?


A linked list is a linear data structure similar to an array. However, unlike arrays, elements are not stored in a particular memory location or index. Rather each element is a separate object that contains a pointer or a link to the next object in that list. Each element (commonly called nodes) contains two items: the data stored and a link to the next node. The data can be any valid data type. You can see this illustrated in the diagram below.




The entry point to a linked list is called the head. The head is a reference to the first node in the linked list. The last node on the list points to null. If a list is empty, the head is a null reference.
In JavaScript, a linked list looks like this:

There are three types of linked lists:

Singly Linked Lists: Each node contains only one pointer to the next node. This is what we have been talking about so far.
Doubly Linked Lists: Each node contains two pointers, a pointer to the next node and a pointer to the previous node.
Circular Linked Lists: Circular linked lists are a variation of a linked list in which the last node points to the first node or any other node before it, thereby forming a loop.




Why do we use Linked List?

Linked lists are preferable over arrays when we need to constant-time insertions/deletions from the list (such as in real-time computing where time predictability is absolutely critical) we don't know how many items will be in the list. With arrays, we may need to re-declare and copy memory if the array grows too big. A linked list is a dynamic arrangement so it can grow and shrink at runtime by allocating and deallocating memory.




How do we use Linked List?

Linked lists are often used because of their efficient insertion and deletion. They can be used to implement stacks, queues, and other abstract data types.




Insert operation on a singly linked list

Inserting a new node before the head (at the beginning of the list).
Inserting a new node after the tail (i.e. at the end of the list).
Inserting a new node in the middle of the list (at a given random position).


