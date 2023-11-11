# MPI-BubbleSort
This repository contains how to execute a bubble sort program in python using MPI with an Ubuntu Master &amp; 3 Ubuntu Slave

# Things to Prepared
1. Ubuntu Desktop Master
2. 3 Ubuntu Desktop Slave
3. MPI (Master dan Slave)
4. SSH (Master dan Slave)
5. NFS (Master dan Slave)
6. Coding Bubble Sort

# Topology
![Topologi](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/2815c150-942f-4296-9ba2-86cf108ad343)

# Configure "etc/hosts/" File
1. Make sure the installed Ubuntu Desktop uses a Network Bridged Adapter, and each Master and Slave are connected to the same internet. Make sure the Master and Slave IPs are known
2. First of all, enter the command to make changes to the /etc/hosts file as shown in the image below.
3. Then, configure etc/hosts in etc/hosts, as shown in the image below
