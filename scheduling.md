

1. **Scheduling -- Process Selection**
When discussing "When to Schedule" in class, it was mentioned that sometimes scheduling could be improved if an 
important process could play a role in selecting the next process to run when it blocks. Give a situation where 
this could be used and explain how.

It could be improved with preemtive scheduling, that means that each process has a limited amount of time. This 
solves the problem when one process gets stuck.

2. **Minimizing Turn Around Time**
Imagine the following list of processes in ready state:


| Process | A | B | C | D | E | F | G | H | Turn Around Time |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Expected run time (msec) | 8 | 5 | 16 | 12 | 55 | 21 | 2 | 34 | 72


---

How should a scheduler order these processes to minimize average turn around time? What is the minimal average turn around time in the optimal order you found?

| Process |G |B | A | D | C | F | H | E | Turn Around Time |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Expected run time (msec) | 2 | 5 | 8 | 12 | 16 | 21 | 34 | 55 | 51.12

Turn Around Time: 51,12

You have to sort it, because it reduces the Turn Around Time.

---

3. **Round-Robin Scheduler --- Discussion**
Round-robin schedulers normally maintain a list of all runnable processes, with each process occurring exactly once in the list. What would happen if a process occurred twice in the list?
