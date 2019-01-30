# axon-server installation (Debian / Ubuntu)

## Prerequisites

Elasticsearch stores all of the collected data by axon-server. Let's install Java 8 and Elasticsearch first.

#### Installing the Oracle JDK

Run the following commands:
``` - 
sudo apt-get install dirmngr
sudo cp /etc/apt/sources.list /etc/apt/sources.list_backup
sudo echo "deb http://ppa.launchpad.net/webupd8team/java/ubuntu xenial main" | tee /etc/apt/sources.list.d/webupd8team-java.list
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys EEA14886
sudo apt-get update
sudo apt-get install oracle-java8-installer
```

Once you've accepted the license agreement the JDK will install.

{!installation/axon-server/elastic.md!}

## axon-server installer
``` -
sudo apt-get install <TODO>

```

{!installation/axon-server/install.md!}


