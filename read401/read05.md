## Linked Lists

### What is a Linked List?
A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

### What does it look like?
![linkedlist](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/images/LinkedList1.PNG)

#### Traversal
When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing. The Next property is exceptionally important because it will lead us where the next node is and allow us to extract the data appropriately.

The best way to approach a traversal is through the use of a while() loop. This allows us to continually check that the Next node in the list is not null. If we accidentally end up trying to traverse on a node that is null, a NullReferenceException gets thrown and our program will crash/end.

When traversing through a linked list, the Current variable will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end.

### Linear data structures
One characteristic of linked lists is that they are linear data structures, which means that there is a sequence and an order to how they are constructed and traversed. We can think of a linear data structure like a game of hopscotch: in order to get to the end of the list, we have to go through all of the items in the list in order, or sequentially. Linear structures, however, are the opposite of non-linear structures. In non-linear data structures, items don’t have to be arranged in order, which means that we could traverse the data structure non-sequentially.

### Memory management

![Memory management](https://miro.medium.com/max/700/1*G43FVT5xJ1n1QDKVNZUxXQ.jpeg)


------------------

resources :

[ Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

[What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

[What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)