<ul>
<li> sudo apt update</li>
<li> sudo apt install openjdk-8-jdk </li>
<li> apt install openjdk-8-jdk -y</li>
<li> wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add - </li>
<li> sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list' </li>
<li> apt-get update </li>
<li> -sudo apt-get install jenkins -y </li>
<li>systemctl status jenkins </li>
<li>sudo ufw allow 8080 </li>
<li> give sudo permisssion to jenkins user < /br>
       vi /etc/sudoers
       and add below entry
       jenkins ALL=(ALL) NOPASSWD: ALL
       and save the file
 </li>
</ul>
