#Github
--------------------------

##Installation
```
sudo apt-get install git
```
[Setting up Git](https://help.github.com/articles/set-up-git/#platform-linux)
```
git config --global user.name "mistletoe999"
git config --global user.email "boyuwei@gmail.com"
```




 [Create a repository on GitHub](https://help.github.com/articles/create-a-repo/)
 
 [Fork a repository](https://help.github.com/articles/fork-a-repo/)
 
 [Create a local clone of a repository](https://help.github.com/articles/fork-a-repo/)
 
 ```
git clone https://github.com/mistletoe999/my_summary.git
```
 sync the local repository
 
 ```
 cd my_summary
 git remote -v
 git remote add upstream https://github.com/mistletoe999/my_summary.git
 
 ```
 


##Push a local repository to Github
[Create a repository on GitHub](https://help.github.com/articles/create-a-repo/) (for the first time): ny_python


```
git add .
git commit -m 'First commit'
```
 add the URL of the remote repository (only the first time)
``` 
git remote add origin https://github.com/mistletoe999/my_python.git
```

Push the changes in your local repository to GitHub.
```
git push origin master
```
- [Adding an existing project to GitHub](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)






##Reference

* http://rogerdudler.github.io/git-guide/
