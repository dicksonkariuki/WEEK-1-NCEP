# WEEK-1-NCEP
This repository contains Linux based scenario questions and answers for Cloud &amp;DevOps Engineers
# File Management Scenarios
1.You accidentally created a file in the wrong directory. How would you move it to:
/home/ubuntu/projects :

  ***mv filename.txt /home/ubuntu/projects*** 

2.Your team needs a folder structure for:
logs
scripts
backups
How would you create all folders using one command?

***mkdir logs scripts backups***

3.A backup file is consuming space. How would you:
locate it
copy it to a backup directory
delete the original

***find /path/to/file  "backup.txt"***

***cp filename backup directoryname***

***rm filename***

4.A web application is failing. The logs are stored in:
/var/log/app.log

How would you:
view the latest logs
continuously monitor updates

***tail /var/log/app.log***

***tail -f /var/log/app.log***

