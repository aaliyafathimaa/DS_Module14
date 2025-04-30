# Ex10 Applications of Queue – FCFS
## DATE: 
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm

1. Start the program. 
2. Input the number of processes. 
3. Input the burst time for each process.
4. Input the waiting time for each process. 
5. Calculate the turnaround time using the formula: Turnaround Time = Burst Time + Waiting Time.  
6. Display the turnaround time for each process.
7. End.

## Program:
```
Program to find and display the priority of the operator in the given Postfix expression
Developed by: Aaliya Fathima
RegisterNumber:  212223230001
```
```
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
   int i;
   for(i=0;i<n;i++)
   tat[i] = burst_time[i] + wait_time[i];
   return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/2954df77-6aa2-42ea-9a31-2923f841d509)


## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
