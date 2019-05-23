# JenkinsDotnet
Automated jenkins job used to create build packaging for Dotnetapplications automatically with in less time and save manual efforts.
This code is written in Groovy command as well as in Windows Batch command.
Groovy script can be created to apply build no to clercase code repository files and apply the build no .
Groovy script used to fetch latest clearcase code and to update the specified code directory.
Windows batch file is created to backup existing files and also to create new folder structure.

Key Benefit and Savings: Saves lots of time of developers to create asp build.
Reduces Manual efforts
Error free code delivery 

How to install:
===========
You'll need the following components installed:
Jenkins insatlled on machine.Available over Internet with the ease.Also setup login user for jenkins.
Jenkins job created with groovy script and windows batch command and provide input as per build input requirement.
Rational Clercase code repository is used as code base to fetch Setup files.
Dotnet compiler should be available to compile or run the setup files .This will create .MSI and .exe files with the compile executable setup.
This is working and tested on windows xp,windows server 2003 .

How to use:
===========
1) Open jenkins tool and select Build with parametres to open the job.
2) Provide input parametres and click on Submit.




Next steps for this asset:
===========

Team Members:<br/>
Sakshi Joshi Sakshijo@in.ibm.com
