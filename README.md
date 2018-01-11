# apache-falcon-pipeline
Apache Falcon Pipeline using HDP 2.6.3

```bash

 su - falcon
 hadoop fs -mkdir /apps/falcon/primaryCluster
 hadoop fs -mkdir /apps/falcon/backupCluster
 hadoop fs -mkdir /apps/falcon/primaryCluster/staging
 hadoop fs -mkdir /apps/falcon/backupCluster/staging
 hadoop fs -chmod -R 777 /apps/falcon/*
 hadoop fs -chown -R falcon /apps/falcon/*
 hadoop fs -mkdir /apps/falcon/primaryCluster/working
 hadoop fs -mkdir /apps/falcon/backupCluster/working
 hadoop fs -chown -R falcon /apps/falcon/*
  hadoop fs -chmod -R 755 /apps/falcon/primaryCluster/working /apps/falcon/backupCluster/working
  cd /usr/hdp/2.6.3.0-235/falcon/
  ./bin/falcon-stop
  ./bin/falcon-start
  ./bin/falcon-status
  ./bin/falcon-start
  ./bin/falcon-status

```
