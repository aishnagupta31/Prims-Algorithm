# BFS Traversal using Adjacency Matrix (C++)

This repository contains a simple C++ program to perform **Breadth-First Search (BFS)** traversal of an undirected graph represented using an adjacency matrix.

---

## 📌 Features

- Takes input for number of vertices and edges
- Constructs an adjacency matrix for the graph
- Performs BFS traversal from a user-specified starting node
- Outputs the adjacency matrix and BFS traversal order

---

## 🧠 BFS Algorithm Overview

Breadth-First Search (BFS) is a graph traversal algorithm that explores all neighbors at the current depth before moving to the next level. It uses a **queue** data structure to keep track of the nodes to be explored.

---

## 🔧 How It Works

1. Input the number of vertices `v` and edges `e`
2. Input each edge (`u v`) – the graph is undirected
3. Print the adjacency matrix
4. Input the starting node `s` for BFS
5. Print the BFS traversal order

---

## 🧪 Sample Input

5 6

1 2

1 3

2 4

2 5

3 5

4 5

1


### 💡 Explanation

- `5 6` → 5 vertices, 6 edges
- Next 6 lines are the edges
- Final input `1` is the BFS starting node

---

## 📤 Sample Output

0 1 1 0 0
1 0 0 1 1
1 0 0 0 1
0 1 0 0 1
0 1 1 1 0
1 2 3 4 5


---

✅ Requirements
C++ compiler (e.g., g++)

Terminal or IDE to run the code

📝 Notes
The adjacency matrix is initialized to 0.

Nodes are 1-indexed.


## 🚀 How to Run

1. **Compile the code**:

g++ bfs_matrix.cpp -o bfs

2. Run the program:

./bfs


You can modify matrix[][101] to handle larger graphs.




