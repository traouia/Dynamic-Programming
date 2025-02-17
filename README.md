# Dynamic-Programming

Dynamic Programming (DP) is an algorithmic technique used for solving complex problems by breaking them into simpler subproblems. 
It is particularly useful for optimization problems where the solution can be built from smaller overlapping solutions.

DP is applicable when a problem exhibits overlapping subproblems and optimal substructure:

* Overlapping Subproblems: The problem can be broken down into smaller subproblems that are solved multiple times.
* Optimal Substructure: The optimal solution of a problem can be derived from optimal solutions of its subproblems.

## Main Components of Dynamic Programming

### 1. Subproblems
* The problem is broken down into smaller, identical subproblems.
* Example: In the Fibonacci sequence, $F(n) = F(n-1) + F(n-2)$, the subproblems are computing $F(n-1)$ and $F(n-2)$.

### 2. Recurrence Relation
* A mathematical formula that defines the solution in terms of its subproblems.
* Example: For the Fibonacci sequence: 
$$ F(n)=F(n−1)+F(n−2)$$
where $F(0)=0$ and $F(1)=1$ are the base cases.

### 3. Memoization (Top-Down Approach)
* A recursive approach that stores the results of subproblems in a table to avoid recomputation.
* This reduces the time complexity from exponential ($O(2^n)$) to linear ($O(n)$).

### 4. Tabulation (Bottom-Up Approach)
* A non-recursive approach where results are stored in an array and built iteratively.

### 5. State transition
* Describes how the solution progresses from one state to another.