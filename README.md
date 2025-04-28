# issa-lab-8-solved
**TO GET THIS SOLUTION VISIT:** [ISSA Lab 8 Solved](https://www.ankitcodinghub.com/product/issa-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119122&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISSA Lab 8 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Concept

› You are going to act as a true Software Engineer in a DevOps environment (“DevOps Engineer” – in marketing terms)

› Based on a given architecture you are going to juggle between all the DevOps main functional areas (System Administration, Infrastructure, Platform and Site Reliability Engineering) and set-up from scratch the necessary tools and a Continuous Delivery System on top.

Arch – Infrastructure

Arch – Infra – Toolchain

1st Part: System Administration Ops (SysOps)

› Purpose: install and set-up the necessary tools

› Points: 1 / 5

Resources

Python 3.x installed

› https://www.python.org/downloads/

Git installed

› https://git-scm.com/downloads

Gitea: https://github.com/go-gitea/gitea/

› Windows: https://github.com/go-gitea/gitea/releases/download/v1.9.4/gitea-1.9.4-windows-4.0-386.exe

› Linux: https://github.com/go-gitea/gitea/releases/download/v1.9.4/gitea-1.9.4-linux-386

XAMPP: https://www.apachefriends.org/

› Windows: https://www.apachefriends.org/xampp-files/7.3.10/xampp-windows-x64-7.3.10-0-VC15installer.exe

› Linux: https://www.apachefriends.org/xampp-files/7.3.10/xampp-linux-x64-7.3.10-0-installer.run

Jenkins: https://jenkins.io/

› Windows: https://jenkins.io/download/thank-you-downloading-windows-installer-stable

› Linux: https://pkg.jenkins.io/debian-stable

File System Layout

› Create the following directory structure either in your main Drive on Windows or in your user home space on Linux

› D:cd-seminary

› ├───code

› └───infra

› ├───gitea

› ├───jenkins

› └───xampp

XAMPP Installation

Please follow the same steps to avoid issues!

Install only selected applications like in the print screen!

XAMPP Bring-up

› Start the Apache Web Server &amp; MySQL Database

› Now access MySQL via the phpMyAdmin interface

› A new tab into your default browser should be open on http://localhost/phpmyadmin/

› Hint: Do not change the port -&gt; if it is used, identify the PID (Go to Xampp -&gt; Netstat) and kill with:

› taskkill /PID &lt;pid_id&gt; /F

MySQL set-up

› A new database has to be created in order to be populated with tables by the Gitea server.

› A separate user has to be created to be used by the Gitea server

› username: gitea | password: gitea

Gitea Bring-up

› Copy the Gitea binary (.exe) into cd-seminary/infra/gitea and run it.

› After the initialization, Gitea should be up on localhost:3000, open the page in a browser.

› Click on either one of the Register or Sign In buttons for the Initial Configuration

› Proceed by filling the fields as shown in the next pages

Part 2 / 3

Part 1 / 3

Part 3 / 3

Hint: in case of error, try to run gitea.exe as admin or delete the folders beside exe file and run it again

Jenkins Bring-up

› Run the Jenkins binary and proceed to install it as shown in the next images. › During Jenkins installation, you can test the port. If it is already used, please deactivate that application from services.msc or see the hint from slide 10

› After the installation ends. Jenkins will be available at localhost:8080

If you encounter an error installing plugins, see links below:

› https://www.phpflow.com/misc/devops/how-to-manually-install-jenkins-plugin/

› https://www.jenkins.io/doc/book/installing/offline/

› Keep the defaults on the next step

› Save &amp; Finish

› Jenkins should be up and you should be logged in with the

‘jenkins’ account

2nd Part: Infrastructure Ops (InfraOps)

› Purpose: Set-up the needed configurations that link the tools in between.

› Points: 1 / 5

Install Gitea Jenkins plug-in

› Access Jenkins pluginManager service and check for Gitea and install it. http://localhost:8080/pluginManager/available

Perform a Jenkins Safe Restart

› Access http://localhost:8080/safeRestart

› Click on Yes

› Wait for the restart

› Log in again (user: jenkins, password: jenkins)

Add Gitea server in Jenkins global scope

› This is done in the system configuration page http://localhost:8080/configure

› Scroll down to the Gitea Server section and Add a new one and then click on Save › If Jenkins can access the server, it should display the Gitea Version

Set-up the Gitea to Jenkins webhook

› We are going to set-up a webhook were Gitea will perform HTTP POST requests each time a new event happens globally.

› This is done on the Gitea side, in site admins settings, in the Webhooks tab. Here is the direct link to it http://localhost:3000/admin/hooks

3rd Part: Platform Ops

› Purpose: set-up the Continuous Delivery environment in Jenkins

› Points: 1 / 5

Create the Gitea organization folder using the plugin

› In the Jenkins home page, click on New Item

› Then proceed to create a Gitea Organization folder

1 / 6

2 / 6

You will be prompted to the Job configuration Page, don’t save yet.

3 / 6

You will be prompted to the Job configuration Page, don’t save yet.

4 / 6

Also you have to add the credentials that have access to the specified organization (Owner)

› These credentials are going to be available only for cd-gitea-ISSA

› Go down into the job configuration page and update the following configurations and Save

4th Part: Site Reliability Engineering Ops (SREOps)

› Purpose: set-up the production environment, software development environment and the required configuration management particularities

› Points: 1 / 5

Create a new Gitea organization

› Access Gitea homepage http://localhost:3000/ and proceed creating your ISSA organization

Create your project Git repository

› From your ISSA’s organization dashboard page http://localhost:3000/org/ISSA/dashboard, proceed creating your project’s Git repository

How to commit a new file(s)

› From your repository page http://localhost:3000/ISSA/project. Via the New File or Upload File

› The New File will prompt your to a page where you can specify the file name (or relative path) and edit it on the spot.

› The Upload File will prompt your to a page where you can drag and drop files to be committed

How to edit a committed file

› From your repository page http://localhost:3000/ISSA/project. Navigate to the desired file to be edited. README.md for example

http://localhost:3000/ISSA/project/src/branch/master/README.md and click on the edit button.

Initial Jenkinsfile

› Commit a new file called Jenkinsfile

› It should have only one line

› sleep 10

› After that go to http://localhost:8080/job/cd-issa-gitea/, the Gitea Jenkins Project that you created at the 3rd Step.

› From the menu of the left, click on Scan Gitea Organization Now.

› Now the ISSA/project repository should have it’s own project folder with it’s own Jenkins job for the master branch that only sleeps 10 seconds at each new change / commit.

Add your project source code

› Go to https://github.com/whymex/issa-cd-fii and port the following files, keeping the directory structure in your Gitea repository

› dev-requirements.txt

› requirements.txt

› project/__init__.py

› project/project.py

› Commit each file individually. 4 Jenkins builds (that still do nothing) should get triggered.

Jenkinsfile code

›Edit the Jenkinsfile from your Gitea repository and copy paste the code from https://github.com/whymex/issa-cd-fii/blob/master/Jenkinsfile

›Observe what’s happening in Jenkins and check the Console Output

›Hint: In case of error, check system environment variable for python and pip.

›After the changes will be done, restart the Jenkins service from services.msc

›Observe what happened in Gitea after the pipeline execution

Fix the code style and make the pipeline succeed

› Fix the variables naming from project/project.py by replacing x and y with first_number and second_number

› Commit the changes and analyze the Jenkins pipeline execution

Exercise: Add a build badge to README.md

›Points: 1 / 5

›The majority of the opensource project have inside their README.md a badge like icon that displays the build / pipeline execution status.

›Example: https://github.com/BurntSushi/ripgrep

›Hints:

›Use the following plug-in and check it’s documentation how to set it up and add the necessary links to your README.md

https://github.com/jenkinsci/embeddable-build-status-plugin ›Allow anonymous users read access at Jenkins.
