# Introduction to DevOps
DevOps combines software development (Dev) and IT operations (Ops) with the goal of shortening the systems devlopment lifecycle and delivering high-quality software continuously.

The key concepts of DevOps:

• Collaboration: DevOps promotes strong collaboration and communication between development, operations, and other stakeholders involved in the software development lifecycle.

• Automation: DevOps encourages the automation of various tasks in the software delivery process, including testing, deployment, and infrastructure provisioning. Automation helps reduce errors and accelerates the release cycle.

• Continuous Integration (CI): Developers regularly integrate their code changes into a shared repository, where automated builds and tests are triggered. This ensures early detection of integration issues.

• Continuous Delivery (CD): It is a practice of continuously delivering software to production, making it ready for release at any point. Continuous Delivery includes automating the entire release process.

• Infrastructure as Code (IaC): Managing and provisioning infrastructure using code, allowing for consistent and repeatable environments. Tools like Terraform and Ansible are commonly used for this purpose.

• Monitoring and Logging: DevOps emphasizes the importance of monitoring application performance and collecting logs for troubleshooting. This helps in identifying and addressing issues quickly.

• Feedback Loops: Constant feedback loops, are essential from both teams and end-users. This feedback helps in improving processes, identifying areas for automation, and enhancing overall software quality.

DevOps is a cultural shift that aligns people, processes, and tools to deliver value to end-users more consistently and efficiently.
# Introduction to Git and git commands
Git is a distributed version control system used for tracking changes in files and is a fast process.Where we link our local repository and Github repository write code and commit into Github repo.
Git is a distributed version control system used for tracking changes in files and is a fast process.Where we link our local repository and Github repository write code and commit into 
1. To Initialize a git repository:
```
 ubuntu@ip-172-31-2-75:~/dir3$ git init
 hint: Using 'master' as the name for the initial branch. This default branch name
 hint: is subject to change. To configure the initial branch name to use in all
 hint: of your new repositories, which will suppress this warning, call:
 hint:
 hint:     git config --global init.defaultBranch <name>
 hint:
 hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
 hint: 'development'. The just-created branch can be renamed via this command:
 hint:
 hint:     git branch -m <name>
 Initialized empty Git repository in /home/ubuntu/dir3/.git/
```

2. To link local and GitHub repo:
```
 ubuntu@ip-172-31-2-75:~/dir3$ git remote add origin <repository url>
```
3. To clone GitHub repository URL:
```
   ubuntu@ip-172-31-2-75:~/dir3$ git clone <URL>
```
4. To add file to staging area:
```
 ubuntu@ip-172-31-2-75:~/dir3$ git add .
```
5. To commit changes from staging area to repository:
```
ubuntu@ip-172-31-2-75:~/dir3$ git commit -m "commit message"
```
6. To check the status of repository:
```
 ubuntu@ip-172-31-2-75:~/dir3$ git status
```
7. To push code into GitHub repo:
```
  ubuntu@ip-172-31-2-75:~/dir3$ git push -u origin master
```
8.To pull code from GitHub:
```
ubuntu@ip-172-31-2-75:~/dir3$ git pull
```
9. To check who has committed:
```
  ubuntu@ip-172-31-2-75:~/dir3$ git log
```
10. to see what code is committed:
```
 ubuntu@ip-172-31-2-75:~/dir3$ git show
 ```





