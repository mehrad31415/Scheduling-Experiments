# Scheduling-Experiments
This was the second project of the operating systems course.

The aim of this assignment is to learn how to design, execute, and report on scheduling experiments performed with the Process Scheduling Simulator.
In experiments 1 to 3 below, the number of processes is 40. There are two kinds of processes (20 of each). All processes arrive at the start. The various times used for one kind of process (duration, CPU burst, I/O burst distribution values) is around four times those used for the other kind of process. All basepriorities are held at 1.0. The quantum for RR is less than the average duration. For simplicity, experiments are conducted with zero time for I/O bursts.


1. Title Slide. 
2. Four criteria by which scheduling can be judged in the order: CPU utilization, Throughput, Turnaround time, & Waiting time.
### Experiment 1 Hypothesis: no difference in results when all distribution values are constant
3. The contents of the psconfig and run files.
4. The contents of the exp file.
5. Box plots of the results for waiting times for RR, FCFS, SJF, and PSJF.
6. Table showing averages for the four scheduling criteria for each
of the four scheduling algorithms in row order RR, FCFS, SJF, and PSJF.
7. Trend check: Box plots showing trend of waiting times for RR as the number of processes is varied:
10,20,30,40,50,60,70,80,90,100.
### Experiment 2 Hypothesis: no difference in results when all distribution values are from the uniform distribution
8. The contents of the psconfig and run files.
9. The contents of the exp file.
10. Box plots of the results for waiting times for RR, FCFS, SJF, and PSJF.
11. Table showing averages for the four scheduling criteria for each
of the four scheduling algorithms in row order RR, FCFS, SJF, and PSJF.
12. Trend check: Box plots showing trend of waiting times for FCFS as the number of processes is varied:
10,20,30,40,50,60,70,80,90,100.
### Experiment 3 Hypothesis: no difference in results when all distribution values are from the exponential distribution
13. The contents of the psconfig and run files.
14. The contents of the exp file.
15. Box plots of the results for waiting times for RR, FCFS, SJF, and PSJF.
16. Table showing averages for the four scheduling criteria for each of the four scheduling algorithms in row order RR, FCFS, SJF, and PSJF.
17. Trend check: Box plots showing trend of waiting times for SJF as the number of processes is varied: 10,20,30,40,50,60,70,80,90,100.
### Investigation
18. Results of stress testing one experiment (Experiment 1) by varying the number of processes non-linearly: 1, 10, 100, 1000, 10000, 100000, 1000000, 10000000, 100000000, 1000000000. A table indicating successful execution (or not) against number of processes. The error when the simulator fails to execute properly.
19. Gantt chart results (four charts) for experiment 3. 


