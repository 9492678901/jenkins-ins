# jenkins-instalation
sudo yum install java-1.8.0-openjdk-devel
sudo update-alternatives --config java -2
 cd /opt/
 sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
 sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
 sudo yum install jenkins
sudo jenkins start


 

