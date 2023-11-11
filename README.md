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
2. First of all, enter the command to make changes to the /etc/hosts file as shown in the image beside.
![PP2](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/a36c1bba-c702-4073-88e4-7465712e5122)
3. Then, configure etc/hosts in etc/hosts, as shown in the image below
![PP1](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/bd4a688c-fb00-416d-9972-e09af1d6b458)

# Make New User
1. On Ubuntu Master and Slave, you need to create a new user with the command
![PP3](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/94cebcd4-5406-4328-b865-d5521ee2dd2f)
Fill in all requests requested by the system, with the user name which must be the same on the Master and each Slave
2. Then in Master and Slave, enter the newly created user with the following command.
![PP4](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/1af57950-95c5-417e-bdec-30b7446f21b2)

# Configurate SSH
1. On Ubuntu Master and Slave, you need to install SSH yourself first with the following command.
![PP5](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/ed5daa69-03a3-4efc-892f-e2e3408c5c1b)

2. Once installed, you can check SSH with the following command.
![PP6](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/86f0191b-ef8a-415c-b7eb-a40e42470feb)

So the result will be like the following image.
![PP26](https://github.com/ShinnoHonobu/MPI-BubbleSort/assets/113822318/6e60cebb-d8aa-42ca-8d46-bfa00491545d)
