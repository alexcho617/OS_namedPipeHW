# OS-hw3

This is one of assignment in from Handong Global Univeristy, Operating Systems class.
Use of this code is not allowed other than the proffessor and TA's

Link of the Video Demo: https://www.youtube.com/watch?v=GByz-qGU-h0&ab_channel=Alexkun

# How To Run
Compile both files separately\n
Run Manager First with following arguments:
./manager <Dir> <key1> <key>

Run Worker 
  ./worker

# pfind
pfind is consists of manager and a worker. Manager will recognize tasks and distribute them to the workers. A task is to find all the keywords and return them

There are 2 major parts.

## Manager
Gets two solution and target c files from commnad line and turns them in to executables.

## Worker
Gets two executables(target, solution) from compiler and one directory which contains all the testcase inputs.
It returns a result report for each of the executables.


# Shortfalls
Queue in Manager,

Feedback from Worker,

Word Search,
