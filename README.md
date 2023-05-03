Download Link: https://assignmentchef.com/product/solved-cs-570-programming-foundations-programming-assignment-6
<br>
<strong>Program #1: 1D Arrays and Sorting (50%)</strong>

You are given the source code for four sorting algorithms, namely, insertion sort, selection sort, quick sort, and merge sort. Each algorithm is implemented in a single java source file, e.g., quick sort is in file <em>QuickSort.java</em>.




<strong>Step 1:</strong> Modify each sorting algorithm so that it keeps track of the number of comparisons it performs and the number of exchanges (swaps) it performs during a single sorting operation. Keep track of these numbers using two long integer counters; one to keep track of the number of comparisons and another to keep track of the number of swaps.




<strong>Step 2:</strong> Write a driver program (i.e., a main program) that instantiates a selection sort, quick sort, merge sort, and insertion sort objects and then instructs each object to sort an array of 50,000 random integer elements, then 100,000 elements, then 200,000 elements, then 300,000 elements, and finally 400,000 elements. Your program should record on the output console the number of exchanges and comparisons for each algorithm and each data set that was sorted. Your program should also keep track of how much time each sorting algorithm needed to sort each array. Hence, for each algorithm you should record the time elapsed for each of the five sorting processes [Hint: use Java’s <em>java.lang.System.currentTimeMillis()</em> method, which returns a long integer that represents the current time in milliseconds. You will need to call this method twice, once just before the sorting process, and once right after the sorting process. The difference will be the time elapsed in milliseconds].







<strong>Program #2: 2D Arrays</strong><strong> (50%)</strong><strong></strong>Write a program to solve the following problem using a 2-dimensional array. A company has 4 salespeople (1 to 4) who sell 5 different products (1 to 5). Once a day, each salesperson passes in a slip for each type of product sold. Each slip contains the following: a) the salesperson number, b) the product number, and c) the total dollar value of that product sold that day. Thus, each salesperson passes in between 0 and 5 sales slips per day. Assume that the information from all the slips for last month is available.




Write a program that will read all this information for last month’s sales and summarize the total sales by salesperson and by product. All totals should be stored in a 2-dimensional array. After processing all the information for last month, display the results in a tabular format, with each column representing a salesperson and each row representing a particular product. Cross total each row to get the total sales of each product for last month. Cross total each column to get the total sales by salesperson for last month. Your output should include these cross-totals to the right of the totaled rows and to the bottom of the totaled columns.




Sample input/output:




Enter sales person number (-1 to end): 1

Enter product number: 4

Enter sales amount: 1082

Enter sales person number (-1 to end): 2

Enter product number: 3

Enter sales amount: 998

Enter sales person number (-1 to end): 3

Enter product number: 1

Enter sales amount: 678

Enter sales person number (-1 to end): 4

Enter product number: 1

Enter sales amount: 1554

Enter sales person number (-1 to end): -1




Product Salesperson 1 Salesperson 2 Salesperson 3 Salesperson 4     Total

1          0.00          0.00        678.00       1554.00   2232.00

2          0.00          0.00          0.00          0.00      0.00

3          0.00        998.00          0.00          0.00    998.00

4       1082.00          0.00          0.00          0.00   1082.00

5          0.00          0.00          0.00          0.00      0.00

Total         1082.00        998.00        678.00       1554.00








