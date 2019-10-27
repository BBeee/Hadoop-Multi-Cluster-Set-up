# Hadoop-Multi-Cluster-Set-up
Configuration Files

## Environment
Virtualbox
-Master node      : Ubuntu 16.04 LTS
-Datanode (Slave1): Ubuntu 16.04 LTS
-Datanode (Slave2): Ubuntu 16.04 LTS


In order to set up hadoop multi cluster with the given configuration files,
hostname for each device should be;
hadoop@master:~$  for Master node
hadoop@slave1:~$  for Datanode 1
hadoop@slave2:~$  for Datanode 2




If you need to change oldname@master to hadoop@master, log out the account.
Then,
1. log in Ubuntu with different account 
2. sudo passwd root
3. su root
4. usermod -l newname oldname
5. usermod -m -d /home/newname newname 



