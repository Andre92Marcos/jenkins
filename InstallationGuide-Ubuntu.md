#Guide to install jenkins in Ubuntu

**1st)  Add the key to your system**

	wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -

**2nd) Then add the following entry in your /etc/apt/sources.list**

    deb https://pkg.jenkins.io/debian-stable binary/

**3rd) Update your local package index, then finally install Jenkins**

    sudo apt-get update
	sudo apt-get install jenkins

**4th) Go to localhost:8080**

**5th) Go to var/log/jenkins/jenkins.log and find the password and input it in the webapp**

**6th) Choose the desired plugins and install**

**7th) Create your first admin user**


**Configurations and Info**


    Jenkins is installed in /var/lib/jenkins

    Jenkins logs can be found in var/log/jenkins/jenkins.log

    The jenkins VM configurations are stored in /etc/default/jenkins
