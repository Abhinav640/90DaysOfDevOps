Exercise:

1. Create a new repository on GitHub and clone it to your local machine

My repo is already created. Below are the steps how you can create the repo.

a. Go to the github.com and create the Repo. Below are the screenshot for reference.

![image](https://user-images.githubusercontent.com/99756745/230297484-fc916729-314c-4a6b-bc20-3092d2d61212.png)

Fill the details and create your new repo.

![image](https://user-images.githubusercontent.com/99756745/230298182-dd5cd5f1-3b28-4bf4-803f-d71b643c0f12.png)

b. Once the repo is created you will have to copy URL of the repo. Below are the screenshot for reference.

![image](https://user-images.githubusercontent.com/99756745/230299742-365e0d4f-afeb-4000-b0c2-9cc1e9da2b36.png)

Now you can clone the repo to your local using the below command.

Command: git clone <copied URL>

![image](https://user-images.githubusercontent.com/99756745/230302346-d73f8fbc-3972-42a1-a9ca-92ba3e60f35a.png)

  
2. Make some changes to a file in the repository and commit them to the repository using Git
  
I have added a new file test2.txt
  
![image](https://user-images.githubusercontent.com/99756745/230302984-3cd81a08-a342-40ae-bfe1-4c5ba86a1234.png)

Now I'll add it an commit it.
  
![image](https://user-images.githubusercontent.com/99756745/230303764-88b47c92-8c90-48c5-91f0-a6c18046884a.png)


3. Push the changes back to the repository on GitHub
  
To push the changes you need to create the access token first. for that you can go to settings >> Developer settings >> Personal access tokens >> Tokens classic >> Generate new token clessic
  
![image](https://user-images.githubusercontent.com/99756745/230304411-3f12e471-951b-49d4-9d5c-f5da5b01ece0.png)

![image](https://user-images.githubusercontent.com/99756745/230304587-030056c2-3a95-40db-ab8e-093c1d8fcfff.png)

![image](https://user-images.githubusercontent.com/99756745/230304876-ef9dec2a-7724-4ef7-9607-492ca8662125.png)

![image](https://user-images.githubusercontent.com/99756745/230305324-4cf45853-3ac3-4987-959c-8474e6468885.png)

Now you can use this token as git password. 
  
Note: save this token some where as it visible only once. on page refresh it will be gone and if you don't remember the toke you have to generate new one.
  
user below command to push the changes.
  
Command: git push origin master
  
![image](https://user-images.githubusercontent.com/99756745/230306375-2f695acc-4e68-4467-b6c3-c90d59d86677.png)

here password is your personal access token.

And the changes are pushed to the github
  
![image](https://user-images.githubusercontent.com/99756745/230306641-57140ff9-82b1-41c1-ad51-fe6584ec8799.png)
