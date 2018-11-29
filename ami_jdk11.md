# install JDK11 @AMI instance

```
wget https://download.java.net/java/GA/jdk11/13/GPL/openjdk-11.0.1_linux-x64_bin.tar.gz
tar -xvzf openjdk-11.0.1_linux-x64_bin.tar.gz 
sudo mv jdk-11.0.1 /usr/lib
sudo alternatives --install /usr/bin/java java /usr/lib/jdk-11.0.1/bin/java 20000
 sudo /usr/sbin/alternatives --config java

```
