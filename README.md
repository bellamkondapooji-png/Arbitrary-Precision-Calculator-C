⚡ APC | Arbitrary Precision Calculator

Breaking the limits of traditional integer data types.
A command-line calculator built using C programming and Doubly Linked Lists, designed to perform 
arithmetic operations on numbers beyond the limits of standard integer data types.
This project explores how large numbers can be represented, processed, and calculated digit by 
digit using dynamic data structures.

🧮 What Makes This Project Interesting?
Unlike conventional calculators that depend on built-in integer limits, APC implements its own 
number representation using linked lists.
Each digit is stored in a node, allowing large numbers to be processed through linked-list operations.

✨ Core Capabilities

Operation                       Description
+                               Addition of large integers
-                               Subtraction of large integers
*                               Multiplication of large integers
/                               Integer division
%                               Modulus operation

⚙️ Under the Hood

Data Structure: Doubly Linked List

Programming Language: C
Key Concepts:
Dynamic Memory Allocation
Pointers and Pointer Manipulation
Doubly Linked List Operations
Digit-by-Digit Arithmetic
Modular Programming
Command-Line Arguments

How Numbers Are Represented
Instead of storing an entire number in a single integer variable, APC stores individual digits 
in linked-list nodes.

HEAD                                TAIL
  |                                   |
  v                                   v
 NULL <- 1 <-> 2 <-> 3 <-> 4 <-> 5 -> NULL

This representation makes it possible to perform arithmetic on numbers of arbitrary length, subject 
to available memory.

🚀 Getting Started
1. Clone the Repository

git clone https://github.com/bellamkondapooji-png/Arbitrary-Precision-Calculator-C.git

2. Navigate to the Project

cd Arbitrary-Precision-Calculator-C

3. Compile

gcc -Wall -Wextra -g *.c -o apc

4. Execute

./apc 123 - 456

Output:
Result: -333

📁 Project Structure
Arbitrary-Precision-Calculator-C/
│
├── main.c
├── list.c
├── add.c
├── sub.c
├── mul.c
├── div.c
├── calculator.h
├── types.h
└── README.md

🧠 What I Learned

Building APC helped me move beyond implementing standard data structures and understand how they 
can solve practical computational problems.

Key takeaways:
Managing dynamically allocated memory.
Understanding and manipulating doubly linked lists.
Designing arithmetic algorithms for large integers.
Breaking a complex problem into independent modules.
Handling edge cases in arithmetic operations.

👩‍💻 Developer

Poojitha Bellamkonda
Electronics and Communication Engineering | C Programming | Data Structures & Algorithms

GitHub Profile

Built with C, curiosity, and a lot of pointer manipulation.
⭐ If you find this project interesting, feel free to explore the code and share your feedback.
