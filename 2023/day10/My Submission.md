## Task 1:

Add a text file called version01.txt inside the Devops/Git/ with “This is first feature of our application” written inside.
This should be in a branch coming from `master`,
[hint try `git checkout -b dev`],
swithch to `dev` branch ( Make sure your commit message will reflect as "Added new feature").
[Hint use your knowledge of creating branches and Git commit command]

- version01.txt should reflect at local repo first followed by Remote repo for review.
  [Hint use your knowledge of Git push and git pull commands here]

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/6e96a650-28cf-4821-b738-3309084a55f5)


  ![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/7dc85d12-d127-45f4-86a7-4500b91a32dd)


Add new commit in `dev` branch after adding below mentioned content in Devops/Git/version01.txt:
While writing the file make sure you write these lines

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/cda0690c-06ef-4276-8940-4f032247bd0c)


- 1st line>> This is the bug fix in development branch

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/1b4c79be-73b4-4a89-ba43-0ce0f2204bf7)


- Commit this with message “ Added feature2 in development branch”

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/e8cbee30-8f35-4a6b-a981-2d1a60f2a257)

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/412f4f85-1e58-414d-b78a-4df94a534b15)


- 2nd line>> This is gadbad code
- Commit this with message “ Added feature3 in development branch

  ![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/c69e1491-bd42-4d4f-ace6-9a8483ae8d10)


- 3rd line>> This feature will gadbad everything from now.
- Commit with message “ Added feature4 in development branch

  ![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/da7bd2b6-bff8-4a64-bac3-43236952a96b)


Restore the file to a previous version where the content should be “This is the bug fix in development branch”
[Hint use git revert or reset according to your knowledge]

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/d54fb062-245f-48e0-a3ec-ba483124aa2e)


## Task 2:

- Demonstrate the concept of branches with 2 or more branches with screenshot.

Before merging

dev Branch

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/db290fcc-0a88-4800-bf8c-5484732bae97)

- add some changes to `dev` branch and merge that branch in `main`

Main Branch

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/425d979f-c308-45c6-b622-fb92e4367996)

After merging into the main branch

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/989f26a8-7a75-40d3-90d8-794a9ed2aacd)

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/b60ccd50-5574-46f8-abde-3e906f5ace2c)


- as a practice try git rebase too, see what difference you get.

The below is before git rebase

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/efbf6598-73f0-4491-8cdf-d69892111716)

The below is after git rebase

![image](https://github.com/Abhinav640/90DaysOfDevOps/assets/99756745/95e83613-4ff3-4d35-94a1-502d51a6e41f)


