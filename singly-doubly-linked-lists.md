# Introduction to Singly Linked Lists and Doubly Linked Lists
Singly linked lists and doubly linked lists are special types of data structures because they introduce the concept of pointers (links) and nodes. A linked list is a collection of similar items called nodes that seek to establish a sequence or order to the collection. There are two types of nodes—head and tail nodes.  Singly linked lists’ nodes can only access the next node, while doubly linked lists’ nodes can access both the previous and next node. The use of the term "singly" or "doubly" represent the number "links" that each node can establish with another node. Think of a line of lawn mowers strung together by rope.

### Singly Linked List
Singly linked lists’ nodes are connected only to the following node. Singly linked lists are great when you want to only access subsequent data. The insertion and deletion of nodes is easy because only the forward pointers of specific nodes need to be modified. Singly linked lists also require less memory than doubly linked lists. However, the main problem with singly linked lists is that directly accessing the previous node is impossible. However, singly linked lists have a problem—they can't access data backwards. For example, imagine you're listening to an album, but the rewind button doesn't work. You can listen to the songs in sequential order, but you can't go back to listen to your favorite one again.

### Doubly Linked List
In contrast, doubly linked lists’ nodes are connected to both the previous and next node. The main advantage of a doubly linked list over a singly linked list is its ability to traverse easily both in a forward and backward direction. This means you now have the ability to rewind the song to the beginning. Doubly linked lists are often used to undo and redo operations and can be used to track or determine the executions of multiple processes. Singly linked lists can also undo operations, but you wouldn't able to "redo"  or "undo the undo" with a singly linked list. But doubly linked lists can be disadvantageous compared to singly linked lists as well. With regards to storage, the extra pointer can be burdensome because extra space is needed to store the extra pointer in a doubly linked list. Also, all operations, such as insertion and deletion, would require more logic to point to both the next and previous nodes. 

## Conclusion
Singly linked lists are implemented in stacks and queues, which are the foundation of computer science. They're great for moving forward, but not so much moving back, like a stereo with a broken rewind button. A doubly linked list, in contrast, is a stereo with functioning rewind and fast forward buttons. Ultimately, both singly and doubly linked lists can be problematic or beneficial depending on the circumstance. Each one has their own unique uses. Linked lists are very important to computer science, and many commonly used features use linked lists. With different types of linked lists, numerous more possibilities still exist, and more functions can be created with the fundamental and simplistic yet important roles of linked lists.

### Works Cited
Wikimedia Foundation. (2023, September 20). Linked List. Wikipedia. https://en.wikipedia.org/wiki/Linked_list  

Garwal, P. (2023, February 15). Advantages and Disadvantages of Linked List. GeeksforGeeks. https://www.geeksforgeeks.org/advantages-and-disadvantages-of-linked-list/  

Mittal, D. (2023, February 23). Applications of linked list data structure. GeeksforGeeks. https://www.geeksforgeeks.org/applications-of-linked-list-data-structure/  

GeeksforGeeks. (2023, April 19). Introduction to Doubly Linked List – Data Structure and Algorithm Tutorials. GeeksforGeeks. https://www.geeksforgeeks.org/data-structures/linked-list/doubly-linked-list/ 
