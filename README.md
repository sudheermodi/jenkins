##installing jenkins
---------------------------------
sudo su -

yum install wget -y

---------------------------------------------------
 sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
 
  sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
  
  yum install fontconfig java-11-openjdk
  
  yum install jenkins
  
  systemctl enable jenkins

systemctl start jenkins

systemctl status jenkins
