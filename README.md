# AWS-benchmarking
bench marking using ycsb and Cassandra with 1 node , 3 nodes , 6 nodes clusters


# Steps Followed: 
1.	Creating instances :
a.	Go to AWS EC2 console and click Launch Instance
b.	Now choose the AMI of your choice ( we choose Ubuntu Server 16.04 LTS (HVM), SSD Volume Type - ami-a58d0dc5)
c.	Choose the type of instance (we choose m4.xlarge)
d.	Configure the instance details:
1.	Configuration 1: Cassandra cluster with 1 node: use 2 instances (1 for Cassandra and 1 for YCSB)
2.	Configuration 2: Cassandra cluster with 3 nodes: use 4 instances (3 for Cassandra and 1 for YCSB)
3.	Configuration 3: Cassandra cluster with 6 nodes: use 7 instances (6 for Cassandra and 1 for YCSB)
