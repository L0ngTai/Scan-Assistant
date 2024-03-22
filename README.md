## DEB Package Installation v1.3.3
- **sudo dpkg -i R7ScanAssistant_amd64.deb**
- **vi /etc/rapid7/ScanAssistant/config.json**
- add key
## RPM Package Installation v1.3.3
- **sudo rpm -ivh R7ScanAssistant_amd64.rpm**
- **vi /etc/rapid7/ScanAssistant/config.json**
- add key 
## Allow port 21047
- **sudo firewall-cmd --zone=public --permanent --add-port=21047/tcp**
- **sudo firewall-cmd --zone=public --permanent --list-ports**
- **sudo firewall-cmd --reload**
