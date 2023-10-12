# Introduction to Queues and Stack Structures  
Queues and stacks are data structures that differ when it comes to the order of which data is processed and changed. The principle for queues is the data that is first in, gets out first. For stacks, the data that is last in, gets out first. 
A queue can be visualized as a sequence of rectangular boxes arranged from left to right with data in each one.  With a stack, the same rectangular boxes are arranged bottom to top, similar to a stack of paper. Queues and stack structures have their own trade-offs, and they both play vital roles in computer science.

### Queues
Queues operate on the principle that the first data to be inserted is the first data to be deleted. Data is inserted at the end of the list and deleted at the front of the list. This principle is called first in first out (FIFO). Think of customers in a line—they are serviced in the order they are in. Queues are at a disadvantage when inserting or deleting data in the middle or end of a queue. This is because one must review the collection of objects starting with the first item until arriving at the desired location in the queue -- very time consuming.  Printers and text messages are good example of where technology uses this first come first serve principle. Printers print in a sequence and text messages are received in the order they were sent (or lease they should).  Queues are unfortunately not great at processing historical events such as last known locations or past mistakes -- that is where stacks come in. 

### Stacks
Image you are a stack of papers. You add to the top of stack and remove from the top of the stack. Stacks follow a last in first out principle (LIFO) and are great in scenarios where prirotiy the most recent item. Stacks are at an advantage over queues when want to find your lost ipods or check your most recent email. But like queues, it is time consuming to access, insert, update, or delete data that is buried deep in a stack structure. You can see examples of stacks in technology with memory management in devices or error logging. Stacks are not great at processing tasks because priority would always be given to the task that arrived last. 

### Recap
Overall, queues and stack structures are essential for many of the operations in modern computer science, and they each have their own unique traits. Queues are the same concept as lines in a store, and stacks can be compared to a stack of plates. Although the principles of queues and stacks are ordinary, the application of these concepts can lead to many different possibilities in computer science.

## Works Cited
Husban. (2023, March 29). Difference Between Stack and Queue Data Structures. GeeksforGeeks.   https://www.geeksforgeeks.org/difference-between-stack-and-queue-data-structures/# 

Aayushi. (2023, February 28). Applications, Advantages and Disadvantages of Stack.    GeeksforGeeks. https://www.geeksforgeeks.org/applications-advantages-and-disadvantages-of-stack/ 

Wikimedia Foundation. (2023, July 31). Queue (Abstract Data Type). Wikipedia. https://en.wikipedia.org/wiki/Queue_(abstract_data_type) 

HackerRank. (2016, September 27). Data Structures: Stacks and queues. YouTube. https://www.youtube.com/watch?v=wjI1WNcIntg 
