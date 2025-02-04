# Queues

Queues are a fundamental data structure in computer science that follow the First-In-First-Out (FIFO) principle. This means that the first element added to the queue will be the first one to be removed. Queues are commonly used in scenarios where order needs to be preserved, such as task scheduling, buffering, and breadth-first search algorithms.

### Basic Operations on Queues
1. Enqueue (Add):

* Adds an element to the end (rear) of the queue.

2. Dequeue (Remove):

* Removes and returns the element at the front of the queue.

3. Peek (Front):

* Returns the element at the front of the queue without removing it.

4. IsEmpty:

* Checks if the queue is empty.

5. Size:

* Returns the number of elements in the queue.


### Types of Queues
* Linear Queue:

A simple queue where elements are added at the rear and removed from the front.

* Circular Queue:

A queue where the last element points to the first element, forming a circle. This avoids wastage of space in linear queues.

* Priority Queue:

Elements are dequeued based on priority (higher priority elements are removed first).

* Double-Ended Queue (Deque):

Allows insertion and deletion from both ends (front and rear).

### Applications of Queues
1. Task Scheduling:

Operating systems use queues to manage processes.

2. Print Spooling:

Print jobs are queued and processed in order.

3. Breadth-First Search (BFS):

Queues are used to traverse graphs level by level.

4. Buffering:

Queues are used in networking to manage data packets.

5. Customer Service Systems:

Queues are used to handle customer requests in order.

![alt text](Queue.png)
