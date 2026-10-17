WiTi Scheduling Algorithm

A C++ implementation of a dynamic programming approach to solve the single-machine scheduling problem, specifically focusing on minimizing the total weighted tardiness (WiTi).

Overview
The algorithm schedules a set of independent tasks on a single machine to minimize the penalty incurred by missing deadlines. It utilizes **Dynamic Programming with bitmasking** to efficiently explore combinations of tasks and find the optimal execution order.

Key Features
* Calculates the exact minimum cost (penalty) for a given set of tasks.
* Reconstructs and outputs the optimal sequence of task execution.
* Processes multiple datasets from a configuration file sequentially.

Tech Stack
* Language: C++
* Algorithm: Dynamic Programming, Bitmasking

Usage
The program requires a text file named `witi.data.txt` in the same directory as the executable. The file should contain datasets formatted with task execution times, weights, and deadlines.

Run
g++ main.cpp -o witi
./witi
