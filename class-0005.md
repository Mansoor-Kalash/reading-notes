# Big O: Analysis of Algorithm Efficiency
describe the Worst Case of efficiency an algorithm can have in performing it’s job.
 
 **This efficiency is evaluated based on 2 factors:**

 1. Running Time
 2. Memory Space



## time complexity 

gives a rough idea of how long it will take an algorithm to execute based on two things: the size of the input it has and the amount of steps it takes to complete.



## space complexity

total amount of space needed to complete the algorithm relate to the amount of input an algorithm has.

we should consider 4 Key Areas for analysis:


 4 Key Areas for analysis:

* ## nput Size

Refer to the size of parameter that pass to Algorithm.

* ## Units of Measurement
When evaluate the tim & space complexity we need these factor:
**for the time :**
1. he time in milliseconds.
2. The number of operations that are executed.
3. The number of “Basic Operations” that are executed.

**for the space**
1. The amount of space needed to hold the code for the algorithm.
2. The amount of space needed to hold the input data.
3. The amount of space needed for the output data.
4. The amount of space needed to hold working space during the calculation.

## Complexity

![complexity](https://miro.medium.com/max/742/1*WBYUz6Lh2Z21DQnEk-MWFQ.png)

# measure big o notation of time
1. the loop consider as O(n).
2. nested loop O(n^2).
3. if the algorithim nees fixe steps to excute O(1).
4. if the loop itrate throw devid in 2 or multiplay by 2 then O(nlogn).

![complexity](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/images/EfficiencyNotations.png)


# LinkedList 

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below image:
![complexity](
https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png)

In simple words, a linked list consists of nodes where each node contains a data field and a reference(link) to the next node in the list.



### Comparing Arrays and Linked Lists

![](https://miro.medium.com/max/1400/1*3IlTLK_S0HmATuYQGxcbUA.png)


