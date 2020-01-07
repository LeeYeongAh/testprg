# testprg yohoyohoyoho yaho  elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic elastic
## prerequistic
* hostname : master is hadoop master
example
```
sudo -i
echo "111.111.111.111 master" >> /etc/hosts
```

### Keyfile
* keyfile name : mykey.pem
```
$ ls
 .gitignore  README.md  do.sh  hive_empdept.sh
 ```
 
 ### install
 ```
 git clone https://github.com/LemonYellowParrot/testprg.git
 cd testprg
 scp ~/mykey.pem ./
 . do.sh
 ```
 
 ### results
 ```
 Time taken: 11.803 seconds, Fetched: 3 row(s)
Query ID = hadoop_20200107050558_50c7299c-4671-47b1-8191-92b041125920
Total jobs = 1
Launching Job 1 out of 1
Status: Running (Executing on YARN cluster with App id application_1578362820332_0011)

Map 1: 0(+1)/1  Reducer 2: 0/1  Reducer 3: 0/1
Map 1: 1/1      Reducer 2: 0/1  Reducer 3: 0/1
Map 1: 1/1      Reducer 2: 1/1  Reducer 3: 0(+1)/1
Map 1: 1/1      Reducer 2: 1/1  Reducer 3: 1/1
OK
20      2518.75
10      2916.6666666666665
Time taken: 1.559 seconds, Fetched: 2 row(s)
OK
dept
emp
Time taken: 0.023 seconds, Fetched: 2 row(s)
ubuntu@ip-172-31-93-138:~/hive_prj$ git clone https://github.com/LemonYellowParrot/testprg.git
Cloning into 'testprg'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
```
 ## Copy Rights
 2020.01 : 
