# DSASolvedProblems
This repo contains all the DSA problems based on Topics with hint(Algorithmn) and leetcode link

| Topic      | Problem Statement |  Leetcode link   |    Hint(Algorithmn)   |  Code  |
| :---        |:----   |:--- | :---     |:--- |
|   Arrays         | Two Sum(Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.You may assume that each input would have exactly one solution, and you may not use the same element twice.) |   https://leetcode.com/problems/two-sum/  | **Approach used** - Iterate the array and check whether hashmap contains the differece of current element from target, If it contains then answer is found else add that element within hashmap along withits index.</br> **Comments**</br>  -1. Two Pointer Strategy would not work here as Array is not sorted and sorting array and finding answer would result in incorrect index</br> 2. First loading complete hashmap and then iterating array and check whether the difference is present as a key would also not work as the given approach would also return the answer by using same element twice |  **Using o(n2) approach** ![image](https://user-images.githubusercontent.com/52998083/181482537-61ce68c9-8b5d-42a4-9b77-43dc97d02c47.png) **Using o(n) approach** ![image](https://user-images.githubusercontent.com/52998083/181487633-e4b00c1b-05ea-4f95-b828-4b1210f58c8a.png)
| :---        |:----   |:--- | :---     |:--- |




