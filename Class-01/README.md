# Azure-class-1

### #find the disk utilization
```
df -h 
```

###  df is used to find the location of the df command in the system.

which : Displays the full path of the command that is used when you type it.

df : A command that reports file system disk space usage.

```
which df 
```

### `who` command in Unix-like systems is used to display a list of users currently logged into the system.

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
# install tools in Linux Server
```
apt update && apt install -y net-tools jq stress nginx python3-pip
```

# nginx file Location:

```
cd /var/www/html
ll
```

```
nano index.nginx-debian.html
```
. change content after open that file.

```
rm -rf html
```


```
git clone -b  DevSecOpsB42 https://github.com/mavrick202/dockertest1.git
```
# install Azure cli in linux

https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux?pivots=apt

# Azure version check
```
az --version
```


# after complete class Delete azure Resource group
