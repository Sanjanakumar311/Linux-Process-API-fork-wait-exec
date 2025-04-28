# Linux-Process-API-fork-wait-exec-
Ex02-Linux Process API-fork(), wait(), exec()
# Ex02-OS-Linux-Process API - fork(), wait(), exec()
Operating systems Lab exercise


# AIM:
To write C Program that uses Linux Process API - fork(), wait(), exec()

# DESIGN STEPS:

### Step 1:

Navigate to any Linux environment installed on the system or installed inside a virtual environment like virtual box/vmware or online linux JSLinux (https://bellard.org/jslinux/vm.html?url=alpine-x86.cfg&mem=192) or docker.

### Step 2:

Write the C Program using Linux Process API - fork(), wait(), exec()

### Step 3:

Test the C Program for the desired output. 

# PROGRAM:

## C Program to print process ID and parent Process ID using Linux API system calls


```c
#include <stdio.h>
#include <sys/types.h>
#include <unistd.h>

int main(void){
    pid_t process_id;
    pid_t p_process_id;
    process_id = getpid();
    p_process_id = getppid();
    printf("The current process id:%d\n",process_id);
    printf("The parent process id:%d\n",p_process_id);
}
```













##OUTPUT

![alt text](image.png)












## C Program to create new process using Linux API system calls fork() and exit()













##OUTPUT








## C Program to execute Linux system commands using Linux API system calls exec() family


























##OUTPUT


















# RESULT:
The programs are executed successfully.
