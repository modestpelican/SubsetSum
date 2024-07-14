# Subset Sum Problem: Proof of NP-Completeness Using Branch and Bound Algorithm

This project provides a C++ implementation to demonstrate the NP-completeness of the subset sum problem using a branch and bound algorithm. The subset sum problem is a classic problem in computer science, which asks if there exists a subset of a given set of integers that sums up to a given target value.

#### Problem Description
The subset sum problem involves determining whether a subset of a given set of integers sums up to a specific target value. This problem is NP-complete, making it challenging to solve efficiently for larger sets.

#### Code Explanation

1. **Global Variables**:
   - `targetFound`: Boolean flag indicating if the target sum subset is found.
   - `solution`: Vector storing the subset that sums to the target.

2. **branchAndBoundSubsetSum Function**:
   - Recursively explores subsets.
   - Base case: stops if index exceeds set size, current sum exceeds target, or subset is found.
   - Includes/excludes current element and recursively checks possible subsets.

3. **Main Function**:
   - Initializes the set `S` and sorts it in descending order.
   - Calls the `branchAndBoundSubsetSum` function.
   - Prints the subset if found, otherwise indicates no solution.

### Key Concepts
- **Branch and Bound**: Efficiently explores potential subsets while pruning paths that exceed the target sum.

This approach highlights the NP-completeness of the subset sum problem by demonstrating the computational effort required to find a solution.

#### Time Complexity
The time complexity of this algorithm is O(2^n), where n is the size of the input set. This is because the algorithm explores all possible subsets of the input set, each of which can either be included or excluded.

#### Space Complexity
The space complexity of the algorithm is O(n), where n is the size of the input set. This space complexity arises due to the space required for recursive function calls, auxiliary data structures like vectors used to store subsets, and the depth of recursion which can be at most equal to the size of the input set.

