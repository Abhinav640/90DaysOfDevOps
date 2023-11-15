1. What is Git and why is it important?

Git is a distributed version control system that allows you to track changes in your source code and collaborate with other developers efficiently.
It is important for the following reasons.

a. **Version Control:** Git tracks changes to your source code over time, allowing you to see the complete history of modifications, who made them, and why.

b. **Collaboration:** Git facilitates collaboration among developers. Multiple team members can work on the same project simultaneously, with changes being merged together seamlessly.

c. **Branching and Merging:** Git's branching and merging capabilities are powerful features that enable developers to work on separate features or bug fixes in isolation. Branches can be created for specific tasks and then merged back into the main codebase once they're complete.

2. What is difference Between Main Branch and Master Branch??

Main and master both refer to the same primary branch. Previously the primary branch was called "Master" however because of its racial factors it was changed to "Main".

3. Can you explain the difference between Git and GitHub?

Git is a distributed version control system that allows developers to track changes in their source code over time.
Whereas GitHub is a web-based platform that provides hosting for Git repositories. 

4. How do you create a new repository on GitHub?

To create a new repository. you need to go to your github home page >> New >> Fill the form >> create repository. Screenshots below for your reference.

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/832fd15a-81a2-46ab-a14e-17721999ebb0)

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/89d2146c-e5a0-4aa9-8f3b-a05765faa6a8)

5. What is difference between local & remote repository? How to connect local to remote?

Local repository: It is a repository that is created locally on your laptop and is not on cloud. No one else can access your repository unless he/she accesses your system.

Remote repository: It is the repository that is on the cloud and you can access it from anywhere and from any system.

Below are the commands to connect to the remote repository.
1. Create a repository on github.

2. Add/Set remote origin.

Command: git remote set-url origin <git-url>

3. git push

Command: git push -u origin <Branch_name>
This will ask you for the user ID and Password.
In the user ID you'll have to put your user ID and in the password, you'll have to put the secret access token that you'll generate from the settings. Below are the steps for the same.
Go to Settings >> Developer Settings >> Personal access tokens >> Tokens (classic) >> Generate new token >> Generate new token (Classic) >> Set the token name and the permissions you want for that token >> Generate Token

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/5e7acc86-cbc0-4770-baed-2e1a23b32d0e)

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/37d20871-419f-4f39-bea2-e8ec25817c57)

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/915bf534-938a-4042-9443-fdc9099c5931)

