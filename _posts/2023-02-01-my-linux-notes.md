---
layout: post
title:  "My Linux Notes"
tags: linux 
---

### Structure

`/etc` is a folder that contains all your system configuratio files.



### Permission

```console

# change the file owner
chown ${your_name} /path_to_ur_file

```


### Screen

```console

# start a screen session
screen -S ${session_name}

## list all screen session
screen -ls 

## go to a screen session
screen -d -r ${PID}

# Back to main session
# ctrl + a + d

# Create new 
# ctrl + a + c

# Navigate
# ctrl + a + n/p


# exit
exit

```

### Network

```console

# get network information
ifconfig

# get ipv4 addr
ip -4 addr

# get all tcp and udp connections
netstat  -a 

# get all tcp connections
netstat -at

# get all active connections
netstat -l

# check if the port usage
netsat -tunlp | grep ${port}


# check port usage 
isof -i:${port}

```


### Sed Command
`SED` is a powerful test stream editor, can do insertiuon, deletion, search and replace

```console

# Replace unix to linux in your file
sed 's/unix/linux' ${file_name} 

# Replace all unix to linux to your file
sed 's/unix/linux' ${file_name}

```

