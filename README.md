# Selection-Greedy-Approcah
 An activity selection problem is to select the maximum size subset of mutually compatible activities.
The activities ai and aj is said to be compatible if si>=fj and [si,fi) and [sj, fj) do not overlap.
Implement greedy activity selection problem.

Input Format

The first line contains positive integer K represents the no of activities in the input file.
 Next line contains K positive integers Sk space separated values of starting time of activities and
 last line contains K positive integers Fk space separated values of finish time of activities.

Constraints

1≤ K ≤ 100

0 ≤ S ≤ 50

0 ≤ F ≤ 100

Consider array index start with 1.

Output Format

For each test case print the compatible activities in sequence.

Sample Input 0

11

1 3 0 5 3 5 6 8 8 2 12

4 5 6 7 8 9 10 11 12 13 14

Sample Output 0

1 4 8 11
"""
