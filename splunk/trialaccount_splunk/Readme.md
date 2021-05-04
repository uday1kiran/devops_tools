wget -O splunk-8.1.3-63079c59e632-linux-2.6-amd64.deb 'https://www.splunk.com/bin/splunk/DownloadActivityServlet?architecture=x86_64&platform=linux&version=8.1.3&product=splunk&filename=splunk-8.1.3-63079c59e632-linux-2.6-amd64.deb&wget=true'
https://download.splunk.com/products/splunk/releases/8.1.3/linux/splunk-8.1.3-63079c59e632-linux-2.6-amd64.deb

dpkg -i debfile


/opt/splunk/bin
./splunk


http://ip:8000

./splunk enable boot-start

systemctl enable splunk
systemctl start splunk

---
redhat:
wget -O splunk-8.1.3-63079c59e632-linux-2.6-x86_64.rpm 'https://www.splunk.com/bin/splunk/DownloadActivityServlet?architecture=x86_64&platform=linux&version=8.1.3&product=splunk&filename=splunk-8.1.3-63079c59e632-linux-2.6-x86_64.rpm&wget=true'

https://download.splunk.com/products/splunk/releases/8.1.3/linux/splunk-8.1.3-63079c59e632-linux-2.6-x86_64.rpm

windows:
https://download.splunk.com/products/splunk/releases/8.1.3/windows/splunk-8.1.3-63079c59e632-x64-release.msi