# Sorting Algorithms & Big O

## Table of Content

- [Project Overview](#project-overview)
- [Main Features](#main-features)
- [Learning Objectives](#learning-objectives)
- [Supported Sorting Algorithms](#supported-sorting-algorithms)
- [Compilation Instructions](#compilation-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)

## Project Overview
The Sorting Algorithms & Big O Project focuses on implementing and analyzing various sorting algorithms, with an emphasis on understanding their time complexities using Big O notation. This project is designed to help students gain practical knowledge of algorithmic efficiency and its trade-offs.

### Purpose
The purpose of this project is to:
* Develop an understanding of different sorting techniques and their use cases.
* Analyze and document the time complexity of sorting algorithms.
* Collaborate in a team setting to solve algorithmic problems.

## Main Features
* Implementation of sorting algorithms, including Bubble Sort, Insertion Sort, Selection Sort, and Quick Sort.
* Documentation of Big O notation for best, average, and worst cases.
* Utilization of arrays and doubly linked lists for sorting operations.
* Collaborative programming environment to foster teamwork and problem-solving skills.

## Learning Objectives
By the end of this project, you will:
* Be able to explain at least four different sorting algorithms.
* Understand the concept and application of Big O notation.
* Learn how to choose the most suitable sorting algorithm for specific inputs.
* Differentiate between stable and unstable sorting algorithms.

## Supported Sorting Algorithms

### What is a sorting algorithm?
A sorting algorithm is a method for arranging elements in a list or an array in a specific order, such as ascending or descending. Sorting algorithms are fundamental in computer science and are used to optimize data access and processing.

| Algorithm           | Description                                    |
|---------------------|------------------------------------------------|
| Bubble Sort         | Repeatedly swaps adjacent elements if they are in the wrong order. |
| Insertion Sort      | Builds the final sorted array one element at a time. |
| Selection Sort      | Repeatedly selects the smallest element from the unsorted portion and places it at the beginning. |
| Quick Sort          | Divides the array into partitions and recursively sorts them. |

## Compilation Instructions
All files are compiled using:
```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c
```
on **Ubuntu 20.04 LTS**.

### Example Compilation for Bubble Sort
```bash
gcc -Wall -Wextra -Werror -pedantic 0-main.c 0-bubble_sort.c print_array.c -o bubble
```

### Example Execution
To run the Bubble Sort algorithm:
```bash
./bubble
```

## Project Structure
```
holbertonschool-sorting_algorithms/
├── 0-bubble_sort.c
├── 1-insertion_sort_list.c
├── 2-selection_sort.c
├── 3-quick_sort.c
├── print_array.c
├── print_list.c
├── sort.h
└── README.md
```

## Contributors
This project was completed as a team effort by:

**Giann Pabon:** [GitHub Profile](https://github.com/) | [LinkedIn Profile](https://linkedin.com/)  
Hi there! I'm Giann Pabon, a passionate developer and contributor to this project. Feel free to check out my work and connect with me on LinkedIn. I’m always excited to network and exchange ideas with fellow professionals!

**Carlos Valentin:** [GitHub Profile](https://github.com/) | [LinkedIn Profile](https://linkedin.com/)  
Hello, I'm Carlos Valentin, a collaborator in this project. I invite you to explore my work and connect with me professionally. Let's share ideas and collaborate!

