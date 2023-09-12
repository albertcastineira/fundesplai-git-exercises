# Ejercicio 1  
  
## 1 Creating the repo
First of all we need to create a new repo on Github. After creating it, we should clone it into our system. We will use the next command: 
```git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY```  

## 2 Creating the readme file & adding it to the current changes  
We create a new file called readme.md, it usually contains basic informations about the project. In our case it will have exercise related things.  
Once we have the file created we have to add it to the current changes, so first of all we will put the next command: 
```git add .```  (This adds all the new files inside the folder)  
Now this files that we added are pending to be pushed to a branch. 

## 3 Pushing the changes to the repo  
To push our changes that we have pending we type the next command:
````git push```  
If we have any type of problems pushing the changes could be one of this problems: 
- We dont have the correct remote path  
 If this is the case we will check for the current remote path with: ````remote -v```  
 This command will show our current remote paths. If its empty we need to make sure that we add the corresponding remote path with: ```git remote add REPO_NAME GIT_USER:GIT_PATH```  

- We dont have any changes ready to push
 If this is the case we will make sure to add the changes using the previous commands.


