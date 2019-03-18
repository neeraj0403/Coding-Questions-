# Coding-Questions-
This repo contains some good coding problems 
 
## 1.Rain Water Trapping
 - **Problem** You are given an input array whose each element represents the height of a line towers. The width of every tower is 1. It starts raining. Water is filled between the gap of towers if possible. You need to find how much water filled between these given towers.
  
  ![m4hyhpw](https://user-images.githubusercontent.com/42520521/50888651-2e4dc800-141c-11e9-8779-08d23eb89474.png)
- **Sample Input**:<br />
2<br />
6<br />
3  0  0  2  0  4<br />
12<br />
0  1  0  2  1  0  1  3  2  1  2  1<br />
 - **Sample Output**:<br />
10<br />
6<br />

[link to the solution](https://github.com/rohitkumar1999/Coding-Questions-/blob/master/RAIN%20WATER%20TRAPPING.java)

## 2.MAXIMUM SUM PATH IN TWO ARRAYS
 - **Problem** You are provided two sorted arrays. You need to find the maximum length of bitonic subsequence. You need to find the sum of the maximum sum path to reach from beginning of any array to end of any of the two arrays. You can switch from one array to another array only at common elements.<br />
 [link to the problem ](https://hack.codingblocks.com/contests/c/611/1290) <br />
 -**Sample Input**:<br />
1<br />
8 8<br />
2 3 7 10 12 15 30 34<br />
1 5 7 8 10 15 16 19<br />
-**Sample Output**:<br />
122<br />
-**Explanation**:<br />
122 is sum of 1, 5, 7, 8, 10, 12, 15, 30, 34<br />
[link to the solution](https://github.com/rohitkumar1999/Coding-Questions-/blob/master/MAXIMUM%20SUM%20PATH%20IN%20TWO%20ARRAYS.java)


## 3.Aggressive Cows
-**Problem**Farmer John has built a new long barn, with N (2 <= N <= 100,000) stalls. The stalls are located along a straight line at positions x1,…,xN (0 <= xi <= 1,000,000,000).

His C (2 <= C <= N) cows don't like this barn layout and become aggressive towards each other once put into a stall. To prevent the cows from hurting each other, FJ wants to assign the cows to the stalls, such that the minimum distance between any two of them is as large as possible. What is the largest minimum distance?<br />

[link to the problem](http://www.spoj.com/problems/AGGRCOW/)<br />

  -**Sample Input**:<br />
First line contains N and C, separated by a single space, representing the total number of stalls and number of cows respectively. The next line contains N integers containing the indexes of stalls.<br />
5 3<br />
1 2 8 4 9<br />

  -**Sample Output**:<br />
  3<br />


## 4.Book Allocation
 -**Problem**You are given number of pages in n different books and m students. The books are arranged in ascending order of number of pages. Every student is assigned to read some consecutive books. The task is to assign books in such a way that the maximum number of pages assigned to a student is minimum.

- **Sample Input**:<br />
First line contains integer t as number of test cases. Next t lines contains two lines. For each test case, 1st line contains two integers n and m which represents the number of books and students and 2nd line contains n space separated integers which represents the number of pages of n books in ascending order.<br />
1<br />
4 2<br />
12 34 67 90<br />

-**Sample Output**:<br />
113 <br />
-**Explanation**:<br />
1st students : 12 , 34, 67 (total = 113) 2nd students : 90 (total = 90) Print max(113, 90)<br />
[link to the problem](https://hack.codingblocks.com/contests/c/611/1263) <br />
