# git Hiddden folder

there is a hidden folder called `.git` which tells you that your project is a git repo

If we want to create a git repo in a new project we' create the folder and inititalize that repo using 'git init'

````
mkdir /workspace/tmp/new-project
cd /workspace/tmp/new-project
git init
touch Readme.md
vi/code Readme.md
git status
git add Readme.md
# make changes to Readme.md
git commit -a -m "add Readme file"

````

# git cloning 

We can clone in 3 ways - HTTPS, SSH, GITHUB CLI

Since we are using Github Codesapces we will create a tmp directory in our workspace.

````sh
mkdir /workspace/tmp
cd /workspace/tmp
````
(1) HTTPS

````sh
git clone https://github.com/anveshk028/Github-Examples.git
cd Github-Examples
````

(2) 



# git commits

when w want to cmmit code , we write we can git commit which will open up the commit edit message in the editor of choice.
```sh
git commit
```
if you are running in your local system it says - you have to set the default "

Set the global editor 
```
ex: git config --global core.editor emacs
```
```
git config --list --show-origin
```

Make a commit and commit message without opening an editor
```sh
git commit -m "added World"
```

# Log

git log will show recent git commits to the git tree

# push

when we want to push a repo to our remote origin
( this wont work cuz we dont have arepo to push - to do that 
git remote add origin )
```
git push
```


# git branches

# git remotes

# git staging 

# git merging

# Add
when we want to stage the chanegs that will be included in the commit, we can use the
...
git add Readme.md
git add .
...

# Reset
Reset allow you to move staged changes to unstaged
This is useful when you don't want to revert all files not to be not committed 
```
git add .
git reset
```

> git reset will revert a git add.

git status shows you what files will or will not be committed. 



# Gitconfig file

The gitconfig file is what stores your global configurations for git such as email, name, editor and more.
showing the contents of your 
.gitconfig file
```
git config --list 
```

When you first install git on a machine you are suppose to set up your name and email

```sh
git config --global user.name "Anvesh K"
git config --global user.email 
165121336+anveshk028@users.noreply.github.com
```
```
Its already setup in below but normally you to also set the editor
```
