## Prep class 3-Linked Lists <a name=" Linked lists"></a>

### Big O: Analysis of Algorithm Efficiency:
Big O’s role in algorithm efficiency is to describe the Worst Case of efficiency an algorithm can have in performing it’s job.
in other words:
Big O(oh) notation is used to describe the efficiency of an algorithm or function. This efficiency is evaluated based on 2 factors:

1. Running Time (also known as time efficiency / complexity):
The amount of time a function needs to complete.

2. Memory Space (also known as space efficiency / complexity):
The amount of memory resources a function uses to store data and instructions.

In order to analyze these limiting factors, we should consider 4 Key Areas for analysis:
- Input Size:Input Size refers to the size of the parameter values that are read by the algorithm,n to refer to the Input Size value.
- Units of Measurement,To evaluate a function for Time and Space complexity,
- Orders of Growth,represents the increase in Running Time or Memory Space.
- Best Case(Big Omega), Worst Case(Big O), and Average Case(Big Theta).
___________________________________________________________________________________________________________
### Linked lists:
A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.
There are two types of Linked List:
- Singly:means that there is only one reference, and the reference points to the Next node in a linked list.
- Doubly:means that there is a reference to both the Next and Previous node.

This is what a Singly Linked List looks like:
![singly linked list](./LinkedList1.png)

### More detailed explanation:
In simple words, a linked list is a data structure that consists of a sequence of elements called nodes. Each node contains two main components: the actual data and a reference (or link) to the next node in the sequence.

Imagine a chain of interconnected nodes, where each node holds some information and points to the next node. The first node is typically called the "head" of the linked list, and the last node points to null or has a "null" reference, indicating the end of the list.

One of the key characteristics of a linked list is its dynamic nature. Unlike an array, a linked list doesn't require a fixed amount of memory at the outset. Nodes can be easily added or removed from the list, making it flexible for managing data.

To access the elements in a linked list, you start from the head node and follow the links to traverse through the list until you find the desired node. This sequential traversal is one of the trade-offs of linked lists since accessing an element at a specific position takes longer compared to an array.

Linked lists are commonly used in computer science and programming because they provide efficient insertion and deletion operations, especially when dealing with large amounts of data. They are often used as the underlying data structure for other more complex data structures like stacks, queues, and graphs.


## Operations on Linked Lists:
1.  Insertion:
- Insertion at the beginning: Create a new node, update the "next" reference to the current head, and set the new node as the head.
- Insertion at the end: Traverse the list until reaching the last node, then create a new node and update the "next" reference of the last node.
- Insertion in the middle: Locate the desired position, create a new node, update the "next" references to connect the new node.
2.  Deletion:
- Deletion at the beginning: Update the head to the next node, and free the memory of the removed node.
- Deletion at the end: Traverse the list until reaching the second-to-last node, update its "next" reference to null or a sentinel value, and free the memory of the removed node.
- Deletion in the middle: Locate the node to be deleted, update the "next" reference of the previous node to skip the node to be deleted, and free its memory.
3.  Searching:
  Traverse the linked list, comparing the data of each node with the target value until a match is found or the end of the list is reached.
4.  Traversal:
  Visit each node in the linked list, usually from the head to the tail, and perform desired operations.

## Example Quiz:
1. What is a linked list?
   1. A data structure with contiguous memory allocation
   2.  A data structure consisting of nodes with references to other nodes
   3. A data structure for binary search operations
2. Which type of linked list allows traversal in both directions?
   1.  Singly linked list
   2.  Doubly linked list
   3.  Circular linked list
3. How can you insert a new node at the beginning of a linked list?
   1.  Update the "next" reference of the last node
   2.  Update the head and set the new node as the head
   3.  Locate the desired position and connect the new node
4. What is the time complexity of insertion and deletion operations at the beginning or end of a linked list?
  1.  O(1)
   2.  O(n)
   3. O(log n)
5. What is one disadvantage of linked lists compared to arrays?
1.  Linked lists provide direct access to arbitrary elements.
2.  Linked lists require contiguous memory allocation.
3.  Linked lists have slower insertion and deletion operations.
    (Note: Answers: 1 - 2, 2 - 2, 3 - 2, 4 - 1, 5 - 3)

