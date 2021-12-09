# CICD
## Github ssh set up
### Testing Jenkins CIg
### Webhooks
![](images/CICD.png)

Task:
Create another job called yourname_ci_merge in jenkins
1.	Create a new branch on localhost called dev
2.	Change main to dev in first job config
3.	Make any changes in your readme on localhost and push for github
4.	If tests passed it should trigger next job - yourname_ci_merge
5.	Merge job should simply merge code from dev to main 

6.	3rd job CD/CDE – should get the code from main 
7.	Deliver to AWs EC2
8.	Cd app
9.	Npm install
10.	Npm start
11.	Final iteration fourth job to deploy and run app
