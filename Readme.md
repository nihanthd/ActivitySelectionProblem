Consider the activity selection problem with N activities from class.
Activity a_i has start time s_i, finish time f_i, and profit of P_i if
it is scheduled.  An activity is *short* if its duration is at most 4
(i.e., a_i is short if f_i-s_i <= 4), and long otherwise.  Consider the
problem of finding a set S of compatible activities to generate maximum
total profit, with the additional restriction that S must have more
short activities than long ones.

Input format:
The input has 1 or more problem instances.  Each instance has the following
format.  The first line has N, the number of activities.  The next N lines
have 3 integers (start, finish, profit) each.  The activities are not given
in any order.

Output format:
One line per problem instance: instance number and its optimal profit.

Sample input:
10

|start|end|profit|
|---|---|---|
|1| 4| 3|
|1|  6| 5|
|25| 28| 3|
|25| 30| 5|
|7 | 12| 5|
|7 | 10| 3|
|13| 18| 5|
|19| 24| 5|
|15| 18| 3|
|22| 25| 3|

Output:
1 19
