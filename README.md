# File-Sharig
This project is made using C - language and LINUX. There are two processes running simaltaneosuly, one is sender and other is receiver code and the sender process is runs in an infinite loop and "n" number of child processes to divide the process overhead and each process assigned a semaphore to make sure that critical section problem that no two or more processes should be in that Critical section at the same time and each child process terminates whenever user enter "quit" and the receiver is also running and soon as sender writes in critical section the receiver reads  that from critical section and then write that data into the file and so on we can read the content anytime using the file directly or just using the terminal as we are in LINUX OS
