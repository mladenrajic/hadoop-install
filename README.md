# Installs hadoop in pseudodistributed mode and hive
  * Hadoop version 3.2.1
  * Hive version 3.1.2
  * OpenJDK version 8
  
  
## Steps
  1. Run `git clone https://github.com/mladenrajic/hadoop-install.git`
  2. Run `cd hadoop-install`
  3. Run `./hadoop-hive-install` (installs the software)
  4. Run `source ~/.bashrc` (setup environment variables)
  5. Run `./hadoop-hive-config` (formats hadoop namenode, creates hive metastore_db, starts hadoop and hive)

## Stopping and Startting hadoop
 * Stop commands
  ** Run `stop-yarn.sh` (stops mapreduce job framework)
  ** Run `stop-dfs.sh` (stops hdfs namenode and datanode)
 * Start commands
  ** Run `start-dfs.sh` (starts hdfs namenode and datanode)
  ** Run `start-yarn.sh` (starts mapreduce job framework)
