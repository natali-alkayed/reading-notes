## Stacks & Queues

* Use an analogy:
Imagine you are at a cafeteria. You have a tray on which you can stack plates and a line of people waiting for their turn to grab a plate. The cafeteria tray represents a stack, while the line of people represents a queue. This analogy will help you visualize how these data structures function.
_ _ _
* Explain a detail in depth:
Let's explore stacks first. A stack is a Last-In-First-Out (LIFO) data structure, just like a stack of plates. You can only add or remove elements from the top of the stack. This behavior is similar to a stack of trays in a cafeteria where you can only add or remove trays from the top.
_ _ _
* Use WHY, WHAT, HOW structure:

1. WHY do we use stacks? Stacks are particularly useful when you need to keep track of the order of elements or perform operations in reverse order. They are commonly used in function calls, undo/redo functionality, and expression evaluation.

2. WHAT operations can we perform on a stack? The primary operations on a stack are:
Push: Add an element to the top of the stack.
Pop: Remove the topmost element from the stack.
Peek: Look at the top element without removing it.

3. HOW do we implement a stack? Stacks can be implemented using arrays or linked lists. We'll discuss the array-based implementation for simplicity.

_ _ _ 
* Write a quiz:

- What is the primary characteristic of a stack?
1. First-In-First-Out (FIFO)
2. Last-In-First-Out (LIFO)
3. Random access
4. None of the above

- Which operation adds an element to the top of the stack?
1. Push
2. Pop
3. Peek
4. Remove

- In which situations are stacks commonly used?
1. Managing function calls
2. Undo/redo functionality
3. Expression evaluation
4. All of the above

_ _ _
- Create a vocabulary/definition list:
* Stack: A Last-In-First-Out (LIFO) data structure where elements are added and removed from the top.
* Push: An operation that adds an element to the top of the stack.
* Pop: An operation that removes the topmost element from the stack.
* Peek: An operation that allows you to look at the top element without removing it.

_ _ _
- Write a cheat sheet:
* LIFO (Last-In-First-Out) data structure.
* Primary operations: push, pop, peek.
* Common use cases: managing function calls, undo/redo functionality, expression evaluation.
* Implementation options: array-based or linked list-based.

_ _ _ 
## Stacks and Queues are both linear data structures that store elements, but they differ in how elements are added and removed.

1. Structure:
- Stack: A stack is a Last-In-First-Out (LIFO) data structure. Elements are added and removed from the same end, often referred to as the "top" of the stack.

- Queue: A queue is a First-In-First-Out (FIFO) data structure. Elements are added to one end, called the "rear" or "tail" of the queue, and removed from the other end, known as the "front" or "head" of the queue.

_ _ _
2. Order of Operations:
- Stack: In a stack, the last element added is the first one to be removed. This follows the LIFO principle, similar to a stack of plates or a call stack in programming. It means that the most recently added element is at the top and gets accessed first.

- Queue: In a queue, the first element added is the first one to be removed. This follows the FIFO principle, like a queue of people waiting in line. It means that the element that has been in the queue the longest gets accessed first.

_ _ _ 
3. Operations:
- Stack: The primary operations on a stack are:
Push: Adds an element to the top of the stack.
Pop: Removes the topmost element from the stack.
Peek: Retrieves the top element without removing it.
Queue: The primary operations on a queue are:

- Enqueue: Adds an element to the rear of the queue.
Dequeue: Removes the frontmost element from the queue.
Peek: Retrieves the front element without removing it.

_ _ _
4. Usage:
- Stack: Stacks are commonly used in scenarios where the order of elements is essential and needs to be maintained. They are often used for function calls, expression evaluation, undo/redo functionality, and backtracking algorithms.

- Queue: Queues are useful when elements need to be processed in the order they arrive. They find applications in task scheduling, process management, breadth-first search, and message passing systems.
 
_ _ _
![stack and queue](./10.png)