![Lottery Scheduling Logo](logo.png)

# Lottery-Scheduling

![Version Details](https://img.shields.io/badge/version-1.0-brightgreen.svg)
![Download Details](https://img.shields.io/github/downloads/mohitesh07/lottery-scheduling/total.svg)
![GitHub contributors](https://img.shields.io/github/contributors/mohitesh07/lottery-scheduling.svg)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

A probabilistic scheduling algorithm for process in operating system. Processes are each assigned some number of lottery tickets based on its priority; and scheduler draws a random ticket to select the next process. Solving the problem of starvation. [See them in action here].

Here some random number of process is generated with different arrival times and different priorities; and an comparison is done to see how much it acts as a priority based scheduler.

Make sure you have must have GCC 5.1.0 installed.

```
gcc --version
gcc (tdm64-1) 5.1.0
Copyright (C) 2015 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

```

### Usage Instructions
Compile the lottery_scheduling.c code using the following instructions;
```
gcc lottery_scheduling.c -o lottery 
```

execute the following command
```
./lottery
```

### Output Format

```
process_no      arrival_timec   Priority
7               1               22947
5               2               1877
3               5               23493
6               5               21240
4               7               14047
0               8               5170
8               8               25008
1               9               15455
2               9               9354


##### LOTTERY SCHEDULING #####

****TOTAL RUNNING TIME=100*****
Running ~ Process id: 7 for 2 sec
enrty_time=1    exit_time=3

Running ~ Process id: 5 for 2 sec
enrty_time=3    exit_time=5

Running ~ Process id: 6 for 2 sec
enrty_time=5    exit_time=7

Running ~ Process id: 4 for 2 sec
enrty_time=7    exit_time=9

Running ~ Process id: 2 for 2 sec
enrty_time=9    exit_time=11

Running ~ Process id: 0 for 2 sec
enrty_time=11   exit_time=13

Running ~ Process id: 2 for 2 sec
enrty_time=13   exit_time=15

Running ~ Process id: 2 for 2 sec
enrty_time=15   exit_time=17

Running ~ Process id: 0 for 2 sec
enrty_time=17   exit_time=19

Running ~ Process id: 0 for 2 sec
enrty_time=19   exit_time=21

Running ~ Process id: 0 for 2 sec
enrty_time=21   exit_time=23

Running ~ Process id: 0 for 2 sec
enrty_time=23   exit_time=25

Running ~ Process id: 0 for 2 sec
enrty_time=25   exit_time=27

Running ~ Process id: 0 for 2 sec
enrty_time=27   exit_time=29

Running ~ Process id: 0 for 2 sec
enrty_time=29   exit_time=31

Running ~ Process id: 0 for 2 sec
enrty_time=31   exit_time=33

Running ~ Process id: 2 for 2 sec
enrty_time=33   exit_time=35

Running ~ Process id: 2 for 2 sec
enrty_time=35   exit_time=37

Running ~ Process id: 0 for 2 sec
enrty_time=37   exit_time=39

Running ~ Process id: 0 for 2 sec
enrty_time=39   exit_time=41

Running ~ Process id: 0 for 2 sec
enrty_time=41   exit_time=43

Running ~ Process id: 0 for 2 sec
enrty_time=43   exit_time=45

Running ~ Process id: 0 for 2 sec
enrty_time=45   exit_time=47

Running ~ Process id: 0 for 2 sec
enrty_time=47   exit_time=49

Running ~ Process id: 0 for 2 sec
enrty_time=49   exit_time=51

Running ~ Process id: 0 for 2 sec
enrty_time=51   exit_time=53

Running ~ Process id: 2 for 2 sec
enrty_time=53   exit_time=55

Running ~ Process id: 0 for 2 sec
enrty_time=55   exit_time=57

Running ~ Process id: 0 for 2 sec
enrty_time=57   exit_time=59

Running ~ Process id: 0 for 2 sec
enrty_time=59   exit_time=61

Running ~ Process id: 0 for 2 sec
enrty_time=61   exit_time=63

Running ~ Process id: 2 for 2 sec
enrty_time=63   exit_time=65

Running ~ Process id: 0 for 2 sec
enrty_time=65   exit_time=67

Running ~ Process id: 0 for 2 sec
enrty_time=67   exit_time=69

Running ~ Process id: 2 for 2 sec
enrty_time=69   exit_time=71

Running ~ Process id: 0 for 2 sec
enrty_time=71   exit_time=73

Running ~ Process id: 0 for 2 sec
enrty_time=73   exit_time=75

Running ~ Process id: 2 for 2 sec
enrty_time=75   exit_time=77

Running ~ Process id: 0 for 2 sec
enrty_time=77   exit_time=79

Running ~ Process id: 0 for 2 sec
enrty_time=79   exit_time=81

Running ~ Process id: 0 for 2 sec
enrty_time=81   exit_time=83

Running ~ Process id: 0 for 2 sec
enrty_time=83   exit_time=85

Running ~ Process id: 2 for 2 sec
enrty_time=85   exit_time=87

Running ~ Process id: 0 for 2 sec
enrty_time=87   exit_time=89

Running ~ Process id: 2 for 2 sec
enrty_time=89   exit_time=91

Running ~ Process id: 0 for 2 sec
enrty_time=91   exit_time=93

Running ~ Process id: 0 for 2 sec
enrty_time=93   exit_time=95

Running ~ Process id: 0 for 2 sec
enrty_time=95   exit_time=97

Running ~ Process id: 0 for 2 sec
enrty_time=97   exit_time=99

Running ~ Process id: 2 for 2 sec
enrty_time=99   exit_time=100 PARTIALLY EXECUTED

Total number of process switch=50


#### ANALYSIS ####
Process ID-->0 Sheduled 34 times; Priority-->5170
Process ID-->2 Sheduled 12 times; Priority-->9354
Process ID-->4 Sheduled 1 times; Priority-->14047
Process ID-->5 Sheduled 1 times; Priority-->1877
Process ID-->6 Sheduled 1 times; Priority-->21240
Process ID-->7 Sheduled 1 times; Priority-->22947
```

# License

[The MIT License (MIT)](LICENSE)
