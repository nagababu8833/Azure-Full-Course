# Azure-class-1
### install tools
```
apt update && apt install -y net-tools jq stress nginx python3-pip
```

### find the disk utilization
```
df -h 
```

### The command which df is used to find the location of the df command in the system.

which : Displays the full path of the command that is used when you type it.

df : A command that reports file system disk space usage.

```
which df 
```

### find The `who` command in Unix-like systems is used to display a list of users currently logged into the system.

Running the command will show something like this:

```bash
user1   tty7         2024-10-03 09:15 (:0)
user2   pts/1        2024-10-03 10:30 (192.168.1.5)
```

Here’s what each column represents:
1. **Username**: The name of the logged-in user.
2. **Terminal**: The terminal (tty or pts) the user is using.
3. **Login Time**: The time when the user logged in.
4. **Remote Host**: If the user is logged in remotely, it shows the remote IP or hostname.

It helps system administrators see who is logged into the machine. Let me know if you'd like further details!
```
who
```
### find the used to display system information.
```
uname -a
```

### find the space of os
```
free
```

### use the command ls -la.

 ls: Lists files and directories.

-l: Lists in long format (detailed view, including permissions, owner, size, etc.).

-a: Lists all files, including hidden ones (files starting with a dot .).

```
la -la 
```


