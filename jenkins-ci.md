#Install Jenkins on Debian


#Update apt-get
```sh
sudo apt-get update
```

##Install JAVA

#Install openjdk-7-jre
```sh
sudo apt-get install openjdk-7-jre
```

#Install openjdk-7-jdk
```sh
sudo apt-get install openjdk-7-jdk
```


#Instal Jenkins
```sh
wget -q -O - https://jenkins-ci.org/debian/jenkins-ci.org.key | sudo apt-key add -
sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian binary/ > /etc/apt/sources.list.d/jenkins.list'
sudo apt-get update
sudo apt-get install jenkins
```