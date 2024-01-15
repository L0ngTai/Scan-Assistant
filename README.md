## DEB Package Installation
- At  a  command  prompt  (in  Linux  also  called  Terminal  Window)  issue  the  following  command from the directory where the Scan Assistant package is located:
- **sudo dpkg -i R7ScanAssistant_amd64.deb**
- **/etc/rapid7/ScanAssistant/config.json**
## RPM Package Installation
- **sudo rpm -ivh R7ScanAssistant_amd64.rpm**
- **etc/rapid7/ScanAssistant/config.json**
## Allow port 21047
- **sudo firewall-cmd --zone=public --permanent --add-port=21047/tcp**
- **sudo firewall-cmd --zone=public --permanent --list-ports**
- **sudo firewall-cmd --reload**
