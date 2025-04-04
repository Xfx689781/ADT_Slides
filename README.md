# Task: Implement Queue ADT and Solve a Problem

### Task Overview:

1. **Implement the Queue ADT** with basic operations like `enqueue`, `dequeue`, `peek`, and `isEmpty`.
2. **Use the Queue** to solve a problem: **Reverse a string using a queue**.

---

### Part 1: Implement the Queue ADT

You need to implement the basic operations of a Queue ADT. The operations you need to implement are:

1. **`enqueue(element)`**: Adds an element to the **end** of the queue.
2. **`dequeue()`**: Removes and returns the **front** element of the queue.
3. **`peek()`**: Returns the front element without removing it.
4. **`isEmpty()`**: Returns `true` if the queue is **empty**, otherwise `false`.

---

### Part 2: Problem – Reverse a String Using a Queue

Now that you've implemented the **Queue ADT**, let's use it to solve a problem.

#### **Problem:**
Write a function `reverseString` that takes a string as input and uses a **queue** to reverse the string.

#### **Instructions:**

1. **Create a Queue** to hold the characters of the string.
2. **Enqueue** each character of the string into the queue.
3. **Dequeue** the characters one by one and store them in a new string.
4. **Return the new string** that contains the characters in reverse order.

#### **Example:**

```javascript
// Test case
reverseString("hello");  // Output: "olleh"