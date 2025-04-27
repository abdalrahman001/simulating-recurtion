# Simulating Recursion - Fibonacci Calculation

This project implements the calculation of the **Fibonacci sequence** by **simulating recursion manually** using a **stack** in C++.  
It demonstrates how recursion works internally by managing the function calls step-by-step without actual recursive function calls.

## How It Works

- A `Call` struct represents each simulated recursive call.
- A `std::stack` holds the pending calls, just like the system call stack.
- The algorithm handles the sequence of operations (locations) manually.
- It calculates Fibonacci numbers iteratively while mimicking recursion.

This technique helps understand recursion, stack frames, and how recursion can be manually converted into iteration.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/abdalrahman001/simulating-recurtion.git
    cd simulating-recurtion
    ```

2. Compile the code:
    ```bash
    g++ main.cpp -o simulate_recursion
    ```

3. Run the executable:
    ```bash
    ./simulate_recursion
    ```

The program calculates and prints `F(n)`, where `n` is defined inside `main.cpp`.

## Example Output

For `n = 5`, the output will be:

