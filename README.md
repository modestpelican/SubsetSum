# Subset Sum Problem: Proof of NP-Completeness Using Branch and Bound Algorithm

This project provides a C++ implementation to demonstrate the NP-completeness of the subset sum problem using a branch and bound algorithm. The subset sum problem is a classic problem in computer science, which asks if there exists a subset of a given set of integers that sums up to a given target value.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [How to Build and Run](#how-to-build-and-run)
- [Code Explanation](#code-explanation)
  - [Header Files](#header-files)
  - [Global Variables](#global-variables)
  - [Branch and Bound Function](#branch-and-bound-function)
  - [Main Function](#main-function)
- [Conclusion](#conclusion)

## Overview

This project demonstrates the NP-completeness of the subset sum problem using a branch and bound algorithm. The algorithm effectively explores all possible subsets to determine if there is one that sums up to the target value, proving the NP-completeness by exhaustive search within feasible bounds.

## Project Structure

- `main.cpp`: Contains the implementation of the branch and bound algorithm to solve the subset sum problem.

## Dependencies

- C++11 or later
- Standard Template Library (STL)

## How to Build and Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/subset-sum-np-completeness.git
   cd subset-sum-np-completeness
