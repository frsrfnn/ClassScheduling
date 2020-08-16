# Group Members
1. Muhammad Haziq bin Sulaiman 1810441
2. Faris Irfan bin Rosemanzailani 1828623
3. Nabila Jahan 1819824
4. Muhammad Nazrin bin Mohd Rofi 1813425

# Introduction

Other than the given FCFS algorithm, our group have choosen SJF and priority scheduling for the other 2 algorithms. The purpose is to 
create a system that is highly dependable and not time consuming. 


# Consideration

We have considered some aspects before choosing SJF and priority scheduling for our project. one of the aspects is time which 
is very suitable with using the priority scheduling since it will execute the highest priority process first hence, will save a lot of time. 
for SJF, it usuallty provides the lowest waiting time for a process. this is what we are looking for in the algorithms we choose which is
to emphasize the use of time to its full potential.


# Analysis
Input:

CSC 2201
duration :2
priority :3
arrival time :1

CSC 3401
duration :3
priority :1
arrival time :3

CSC 1103
duration :1
priority :4
arrival time :2

CSC 1405
duration :4
priority :2
arrival time :4


## FCFS
first come first serve (FCFS) basis as the process which arrives first will be executed first or in other words that the process which requests the CPU first gets the CPU allocation first. FCFS is the basic of CPU scheduling algorithm. FCFS algorithm does not include any complex logic, all the process is put in queue and executed accordingly which avoids starvation from occuring.

average waiting time : 3.25
average turn around time : 5.75

## SJF
shortest job first (SJF) scheduling works by executing the process with the shortest burst time in the first place resulting in the reduction of average waiting time for the next process. this will increase the efficincy of the system hence, more process can be done in a shorter time frame.

average waiting time : 1.33
average turn around time : 3.33

## PRIORITY SCHEDULING
Priority schudeling will prioritize process with higher priority. the process with higher priority will be executed first followed by the other processes with lower priority. 

average waiting time : 5
average turn around time : 8
