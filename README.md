Budget Trip Planner (C)
A simple C program that helps select the best cities to visit within a limited budget by maximizing enjoyment.
🚀 Features
Input cities with cost and enjoyment
Compares:
Greedy approach
Dynamic Programming (Knapsack)
Displays optimal city selection and total enjoyment
🧠 Algorithms
Greedy → Fast, based on enjoyment/cost ratio
Dynamic Programming → Optimal solution using 0/1 Knapsack
▶️ How to Run
gcc trip_planner.c -o trip
./trip
📊 Example
Input:
4
10 60
20 100
30 120
25 90
50
Output:
[Greedy Plan]
Cities selected: 1 2

[DP Optimal Plan]
Cities selected: 3 2
Maximum Enjoyment: 220
🎯 Key Insight
Greedy is fast but not always optimal, while DP guarantees the best solution.
📌 Tech Stack
C (stdio.h)
