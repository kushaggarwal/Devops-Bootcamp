### Installation on Ubuntu

Installing Java ( Pre requisite )

`sudo apt update`

`java -version`

`sudo apt install default-jre`

`java -version`

`sudo apt install default-jdk`

`javac -version`

Jenkins installation Commands

`wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key |sudo gpg --dearmor -o /usr/share/keyrings/jenkins.gpg`

`sudo sh -c 'echo deb [signed-by=/usr/share/keyrings/jenkins.gpg] http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'`

`sudo apt update`

`sudo apt install jenkins`

`sudo systemctl start jenkins.service`

`sudo systemctl status jenkins`

NOTE - In case face any issues in starting Jenkins, make sure to restart the EC2 instance for the changes to take effect
