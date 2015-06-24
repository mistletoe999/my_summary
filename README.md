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
 
[Create a local clone of a repository](https://help.github.com/articles/fork-a-repo/): my_summary
 

 
 
```
git clone https://github.com/mistletoe999/my_summary.git
```
sync the local repository
 
```
cd my_summary
git remote -v
git remote add upstream https://github.com/mistletoe999/my_summary.git
```
 
git pull origin master
 
 
 
##Push a local repository to github 
 
[Create a repository on GitHub](https://help.github.com/articles/create-a-repo/): my_python  (for the first time)
 
Create and initialize a local repository (for the first time) 
```
mkdir my_python
cd my_python
git init
```

Add files to the local repository
```
git add --all
```
Commit the files in the local repository
```
git commit -m 'First commit'
```
Add the URL for the remote repository: (for the first time)
```
git remote add origin https://github.com/mistletoe999/my_python.git
```
Push the local repository to GitHub
```
git push origin master
```



##Reference

* http://rogerdudler.github.io/git-guide/
