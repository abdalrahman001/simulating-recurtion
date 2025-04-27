Fibonacci Iterative Simulation
This project implements a Fibonacci number calculation by simulating recursion manually using a stack data structure.
It mimics how recursion works internally, but without using real function calls!

How it works
A Call struct represents the state of each "recursive call."

A std::stack is used to manage the calls manually.

The algorithm handles the function's call locations and return values step-by-step, like a real call stack.

This technique helps understand how recursion can be transformed into iteration.

How to run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Compile the code:

bash
Copy
Edit
g++ main.cpp -o fib
Run it:

bash
Copy
Edit
./fib
You can also edit n inside the main() function to compute different Fibonacci numbers.

Example output
If n = 5, the program outputs:

r
Copy
Edit
F(5) = 5
Why simulate recursion?
To understand how function calls and returns are managed internally.

To optimize recursive algorithms and prevent stack overflows.

To prepare for advanced algorithm techniques like dynamic programming.

