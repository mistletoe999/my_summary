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



##Pull changes in Github to local repository
 
[Fork a repository](https://help.github.com/articles/fork-a-repo/)  (for the first time)
 
Create a local clone of a repository  (for the first time)
 
```
git clone https://github.com/mistletoe999/my_summary.git
```

Pull changes in Github to local repository 
 ```
git pull origin master
``` 
 
 
##Push a local repository to Github 
 

 
Create and initialize a local repository (for the first time) 
```
mkdir my_python
cd my_python
git init
```
[Create a repository on GitHub](https://help.github.com/articles/create-a-repo/): my_python  (for the first time)

Add the URL for the remote repository: (for the first time)
```
git remote add origin https://github.com/mistletoe999/my_python.git
```


Add files to the local repository
```
git add --all
```
Commit the files in the local repository
```
git commit -m 'First commit'
```


Push the local repository to GitHub
```
git push origin master
```



##Reference

* http://rogerdudler.github.io/git-guide/
