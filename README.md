# Jenkins

sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo

sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key

yum install fontconfig java-17-openjdk

yum install jenkins

systemctl start jenkins

systemctl enable jenkins

systemctl status jenkins
  
