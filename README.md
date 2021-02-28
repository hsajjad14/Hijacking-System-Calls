### Hijacking-System-Calls

kernel module to be installed on the Linux kernel to intercept system calls.

Used kernel initialization to redirect a system call in the kernel’s system call table to my custom systemcall.

Custom system call has the ability to also intercept other system calls and monitor which processes are being used by certain system calls.
