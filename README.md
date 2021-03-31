# Ebola_crisis


There are people randomly seated in an NxN grid.
In the grid a 0 means an empty seat. A positive integer denotes a person.
A person can be numbered from 1 to 5, 1 meaning he is perfectly healthy whereas 5 meaning he is highly infected with the virus.
Any person who is directly adjacent to an infected person (left-right-up-down-diagonally adjacent) is at a high risk.
If a healthy person numbered 1 is adjacent to an infected person numbered 3, he is at high risk 3, and so on.

Your task is to calculate the number of infected-k people for k = {2,3,4,5} and also the number of high risk-k people for k = {2,3,4,5}

Note that if person is beside multiple infected people, he is at risk for the highest level of infection.

Input
First line contains the size of the grid N.
Next contains the NxN grid.

Output
Print 8 integers in the following format :

infected-2 infected-3 infected-4 infected-5  
highrisk-2 highrisk-3 highrisk-4 highrisk-5


Sample Input 0
5
0 0 0 1 5
1 1 1 1 1
3 1 2 1 0
1 1 1 1 1
4 4 1 3 1


Sample Output 0
1 2 2 1
2 6 4 3
