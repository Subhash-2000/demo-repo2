#Demo2

Doing something just get into know git commands.

1. In this git lesson we created the demo-repo2 folder directly in vscode then inside that we created README.md file then we did a cd ../demo-repo2
2. Then we did git init into it then we check the status of the folder 
3. Next what we did is git add . then git commit -m "title message" -m "description message"
4. But as we have created the folder dirctly without cloning from github. So it wont enable us to push to repository as it only dont know which repo to push.
So, We want to create a repository in github then copy that https url and put it in the below shown command.
5. git remote add origin httpsurllinkoftherepo 
6. then git remote -v [this command will show any remote repository that connected to this repository]
7. Then just type git push origin master 
(or)
git push -u origin master [By this command in next time i dont want to type fully like this rather i can type as git push thats it]
{-u means upstream, its basically we are setting default to push any changes}
By this we have successfully added the folder/project to github

Doing git braching:

1. We went to folder called demo-repo then we type command called "git branch" which will shows current branch that we are in that repository.
2. Then the commad called git checkout [Which will basically ussed to switch between branches]
But to tell to create a new branch we use command like -b feature-readme-instruction [git checkout -b branchNameToCreate]
