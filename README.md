sudo su
cd /
mkdir test
sudo curl -L -o /etc/yum.repos.d/corretto.repo https://rpm.releases.hashicorp.com/AmazonCorretto/corretto.repo
sudo yum install -y java-11-amazon-corretto-devel
touch a.java
vim a.java
javac a.java
java a
