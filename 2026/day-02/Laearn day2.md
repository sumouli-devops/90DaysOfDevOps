Process States (Simple & Practical)
•	Running (R)
o	Process is currently using the CPU or ready to run.
o	Example: a script or app actively executing.
•	Sleeping (S)
o	Waiting for an event (I/O, user input, network response).
o	Very common state; normal behavior.
•	Uninterruptible Sleep (D)
o	Waiting for disk or hardware I/O.
o	Cannot be killed easily (even with kill -9).
•	Stopped (T)
o	Process paused by a signal (like Ctrl + Z) or debugger.
o	Can be resumed later.
•	Zombie (Z)
o	Process finished execution but parent hasn’t collected its status.
o	Uses no CPU, but still appears in process list.
o	Too many zombies = bad process handling.
________________________________________
5 Commands Used Daily (Must-Know)
•	ps
o	Check running processes.
o	Example: ps -ef
•	top / htop
o	Real-time CPU, memory, and process monitoring.
•	grep
o	Search text/logs quickly.
o	Example: grep error logfile.log
•	cd
o	Navigate between directories.
o	Example: cd /var/log
•	ls
o	List files and folders.
o	Example: ls -l

