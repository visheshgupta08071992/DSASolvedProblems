# DSASolvedProblems
This repo contains all the DSA problems based on Topics with hint(Algorithmn) and leetcode link

| Topic      | Problem Statement |  Leetcode link   |    Hint(Algorithmn)   |  Code  |
| :---        |:----   |:--- | :---     |:--- |
|   Arrays         | Two Sum(Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.You may assume that each input would have exactly one solution, and you may not use the same element twice.) |   https://leetcode.com/problems/two-sum/  | **Approach used** - Iterate the array and check whether hashmap contains the differece of current element from target, If it contains then answer is found else add that element within hashmap along withits index.</br> **Comments**</br>  -1. Two Pointer Strategy would not work here as Array is not sorted and sorting array and finding answer would result in incorrect index</br> 2. First loading complete hashmap and then iterating array and check whether the difference is present as a key would also not work as the given approach would also return the answer by using same element twice |  **Using o(n2) approach** ![image](https://user-images.githubusercontent.com/52998083/181482537-61ce68c9-8b5d-42a4-9b77-43dc97d02c47.png) **Using o(n) approach** ![image](https://user-images.githubusercontent.com/52998083/181487633-e4b00c1b-05ea-4f95-b828-4b1210f58c8a.png)
| Arrays     |Target Sun Pair(Given an array of integer consisting of all the unique elements and a target. Print all the pairs forminf the target. If the pair is printed then it should not be printed again</br> **example** - {7,15,3,18,6,4,19,2,12,8,9} Target -15 if {7,8} is printed then {8,7} should not be printed |(https://github.com/visheshgupta08071992/JavaPractise/blob/master/src/main/java/DSAPreparation/Grind75/Array/TargetSumPair.java) | Sort the Array and use two pointer strategy. Find sum of first and last element and keep on increasing and decresing the pointer</br> **Comments** - Hashmap would not work here as we want unique pairs  |**Complexity o(nlogn)** ![image](https://user-images.githubusercontent.com/52998083/181497150-5c2561aa-01f8-4280-a211-ada59cb595a8.png)
 |




