# Stack-implementation-using-array














# Algorithm
1st code of stack implementation:
1) Node Class: Represents a single linked list node with value and pointer next.
2) Constructor: Initializes a node with given data and sets next to NULL.
3) insertAtHead Function:
Creates a new node
Sets its next to the current head.



2nd Code of Stack Implementation:
Node Class: Represents a node with an integer value and a pointer to the next node (next).

Constructor: Initializes the node with given data and sets next to NULL.

insertAtHead Function:

1) Creates a new node:
Sets its next to the current head.
Updates head to point to the new node.
insertAtTail Function:

2) Creates a new node:
If the list is empty, sets head to the new node.
Otherwise, traverses to the end of the list and links the new node.
display Function:

3) Traverses the linked list from head:
Prints each node's value followed by a space.
Ends with "NULL" to indicate the end of the list.
main Function:

 4) Initializes the linked list with head set to NULL.
Inserts values (4, 5) at the head and displays the list.
Inserts values (3, 6) at the tail and displays the list.


5) Traverses the linked list from head:
Prints each node's value followed by " -> ".
Ends with "NULL" to indicate the end of the list.


6) main Function:
Initializes the linked list with head set to NULL.
Inserts values (4, 5, 10) at the head.
Displays the linked list after each insertion


Code 3 Algorithm:
