  1   sudo yum update -y #update your mashion

  2   sudo wget -O /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/redhat-stable/jenkins.repo #download pacages from website
 
  3   sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key #import key from jenkins
 
  4   sudo yum upgrade # upgrade your mashiomn 
 
  5   sudo dnf install java-11-amazon-corretto -y # installa java 11 version
 
  6   sudo yum install jenkins -y #install jenkins
 
  7   sudo systemctl enable jenkins #enable jenkins 
 
  8   sudo systemctl start jenkins #start jenkins
 
  9   sudo systemctl status jenkins #check jenkins status
 
  10  sudo cat /var/lib/jenkins/secrets/initialAdminPassword # view innitial password
