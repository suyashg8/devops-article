# devops-article
 DevOps Assignment

Name: Suyash Gupta

E-Mail: suyashgupta.nov8@gmail.com


For the task given by Vimal sir, I was able to complete the task.

Concepts covered :

1) creating branches of github repo for two developers

2) creating a script which pushes the git repo automatically

3) creating jobs which automatically download the repo on linux system once changes are commited to github for two developers separately.

4) creating jobs for tester and qat

5) job for merging
My Completed parts of the task


The repo created for this purpose: https://github.com/suyashg8/devopssample 


Two branches were created namely master and dve1.


The first job :"jobformaster" was made in order to auto update the files in /var/www/html when we push the repo in the master branch of devopssample in my windows OS.

the second job :"jobfordev1" was made in order to auto update the files in /var/www/html when we push the repo in the dev1 branch of devopssample in my windows OS.

The files are getting updated in the destination folder and can be accessed via public ip created by running the ./ngrok http 80 in terminal.

Job 3 :jobforserver1

jobfortester  :

CAT job for merge : for merging with master



