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

# File viewing and Management scenarios

4.A web application is failing. The logs are stored in:
/var/log/app.log

How would you:
view the latest logs
continuously monitor updates

***tail /var/log/app.log***

***tail -f /var/log/app.log***

5.You suspect the application has database errors. How would you search the log file for:
ERROR

***grep "ERROR" path to the log file***

6.A configuration file is very large, which command would help you scroll through it page by page?

***less filename.config***

# Permissions & Owernship Scenarios 
7.A deployment script called:
deploy.sh
fails with: Permission denied
How would you fix it?

***chmod +x  deploy.sh***

8.You want only the owner to:
read
write
execute
a file.
Which permission number would you use?

***chmod 700 file.sh***

9.A file belongs to the wrong user.How would you change ownership to: ubuntu

***Sudo chown ubuntu filename.txt***

10.You accidentally gave everyone write access to a sensitive file.  Why is this dangerous?
***Sensitive files can be tampered with by malicius actors,there can be accidental corruption or deleting***












