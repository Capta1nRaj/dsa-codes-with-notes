# 1. What is Data Structure?

- It is a way to organize data, so that, we can use that data in an efficient manner.

# 2. Types of Data Structure:-

There are 2 types of DS:-

- (i.) Primitive DS:- Basic types of data.
- (ii.) Non-Primitive DS.

## There are 4 types of Primitive DS:-

- (i.) Integer
- (ii.) Float
- (iii.) Character
- (iv.) Pointer

## There are 3 types of Non-Primitive DS:-

- (i.) Array
- (ii.) Lists
- (iii.) Files

### There are 2 types of List:-

- (i.) Linear List:- It is of 2 types Stacks, & Queues. In Linear List, operation can be performed on starting or ending of the array, you can't perform any operation in between.
- (ii.) Non-Linear List:- It is of 2 types Graphs, & Trees. In Non-linear List, operation can be performed from any point of the array.

# Operations of DS:-

- (i.) Traversal:- It means to just check/read the data.
- (ii.) Insertion:- Inserting a value in the data.
- (iii.) Deletion:- Deleting a value in the data.
- (iv.) Searching:- Searching a value in the data.
- (v.) Sorting:- Sorting the data.
- (vi.) Merging:- Merging 2 data in one.

# 3. Types & Operations of DS we will study:-

- (i.) Array
- (ii.) Stack
- (iii.) Queue
- (iv.) Tree
- (v.) Graph
- (vi.) Insertion
- (vii.) Recursion
- (viii.) Search
- (ix.) Sorting
- (x.) Merge
- (xi.) Map
- (xii.) Set

## 4. Studied:-

- Array traversion in video_2_array_traversion.html.
- Insert a value in an array in video_3_insert_a_value_in_array.html, & also learned **.splice(indexWhereToAdd, HowManyToElemntsAdd, ElementsToAddSeperatedByComma)** method.
- Delete a value in an array in video_4_delete_a_value_in_array.html, & also learned in-built js method to remove an element from the array **.splice(indexFromWhereToDelete, totalElementsToDelete)**
- Search an element in an array in video_5_search_element_in_array.html, & also learned **.indexOf(element)**, shortcut method to find any element position in an array.
- Merge 2 Array in video_6_merge_two_array.html, & also learned **...** spread method to merge two arrays.
- Merge 2 Array in video_7_merge_two_array_with_while_loop.html.

# 5. Algorithm Complexity:-

- What is Alog Comp:- Steps to do anyting.
- There are two type of complexity:-
- (i.) Space Complexity, it means memory taken by the function/code to execute.
- (ii.) Time Complexity, it means time taken by the function/code to execute, or amount of space required to solve a problem. Lesser the number of lines of the code took to execute has better the time complexity. Space Comp = Auxilary Space + Input Size.
- Whenever we made a program, we must check time & space complexity.
- Lets discuss more about this per file video_6(file6) & video_7(file7).
- in file6, it took 21 lines of the code to execute, whereas file7 took 38 lines. So file6 is better in comparision to file7 because it will execute faster in comparision for time complexity.
- Now let's talk about Space Complexity, in file6, the space complexity is 4, whereas in file7, it is 6. So file6 is still faster than file7 in terms of space complexity.
- But here is a catch if someone says you must sort the array too, so file6 will take long time in comparision to file7.
- Big O notation:- Use to denote the complexity of the program.
- For double loop:- f(n) = n² = Time Complexity.
- Example:- f(n) = 5n² + 6n + 12, 5 means the loop inside the loop will have 5 lines, 6 means the main loop will have 6 lines, & 12 means static lines of the code. But mostly we will calculate 5n² as 6n + 12 value doesn't matter that much.

# 6. Asymptotic Analysis & Notation:-

- What is Asymptotic Analysis:- It provides a high-level understanding of how an algorithm performs with respect to input size.

# 7. Array Data Structure/Sorting:-

## Bubble Sorting:-

If you want to sort an array using bubble sorting, you will need a loop to run n² times. Eg.:- let x =[4,8,10,6], so this loop will run 4 x 4 = 16 times. Code in video_10_bubble_sorting.html.

# 8. Recursion:-

- It is a process in which a method calls itself to solve some problem.
- There are 2 types of recursion:-
  1. Direct recursion:- If the function is called inside same function it is called direct recursion. Explained in video_11_recursion.html.
  2. Indirect recursion:- If the function is called to a different function it is called direct recursion. Explained in video_12_indirect_recursion.html

## Head & Tail Recursion:-

* How debugger works:- Watch this [video](https://www.youtube.com/watch?v=vzTqM04YbiY&list=PL8p2I9GklV47TMMnPzqnkCtSOS3ebr4O7&index=16).
* What is call stack:- Watch this [video](https://youtu.be/vzTqM04YbiY?list=PL8p2I9GklV47TMMnPzqnkCtSOS3ebr4O7&t=586).
* Head & Tail Recursion more explained in this[ video](https://youtu.be/vzTqM04YbiY?list=PL8p2I9GklV47TMMnPzqnkCtSOS3ebr4O7&t=1068).
* Reverse an array using recursion in video_14_reverse_array_with_recursion.html, & JS default have an in-built reverse function i.e.:- data.reverse();

# 9. Stack Data Structure:-

- What is stack:- It is a linear DS & also called LIFO.
- Eg.:- Stack, Queue, Array.
- Eg. of non-linear DS:- Tree, Graph.
- In Stack DS, operations are performed as LIFO or FILO only.
- In Stack DS, you can not find any data in between of an array.
- When we defined stack, we always find the max value.
- There are mainly 2 operation in Stack DS i.e. Push & Pop.
- Some other operations are:- isEmpty(), peak().
- What is callByReference:- What [video](https://youtu.be/iXxHiad2uI4?list=PL8p2I9GklV47TMMnPzqnkCtSOS3ebr4O7&t=962).

# 10. Queue Data Structure:-

- It is also a linear DS, but it is called FIFO.
- Euqueue:- Add item in queue in front.
- Dequeue:- Remove item in queue in end.

## Circular Queue DS:-

- A circular queue is the extended version of a regular queue where the last element is connected to the first element.

# 11. Search Algorithms:-

- There are 2 types of search algorithms:-
  - Linear.
  - Binary.
- Interview Questions:-
  - How many types of Search Algo are there?
  - Linear search complexity:- O(n).
