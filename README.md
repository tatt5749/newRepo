# git-101
Introduction to Git

## Slide
[Git 101 Slide](http://bit.ly/cc-git-slide)

## Check Version
	`git --version`

## Open Help File
	`git help config`

## Clear Screen
	`clear`

## Config name & email
	`git config --global user.name "Nasrul"`
	`git config --global user.email "nasrulhazim.m@gmail.com"`

## Initialized empty Git repository
	`git init`

## List files
	`ls`
	`ls -la`

## Create new file
	`touch [file name]`

## Stage File/Folder
	`git add [file/folder]`

## Stage All
	`git add *`

## Stage Based on rules
	`git add *.php`

## Commit with message
	`git commit -m "your message here"`

## Check History
	`git log`
	`git log --pretty=oneline`

## Remove files / folder
	`git rm [files/folder]`
	`git commit -m "removed [files/folders]"`
	** add -r for delete recursively for directory

## Git Add & Commit
	RULES: FILES / FOLDERS STATUS MUST BE MODIFIED
	`git commit -a -m "add and commit only for modified files"`

## Git Ignore
	create .gitignore
		- specific file [filename]
		- wildcard *
		- exception (!)

## Cloning
	`git clone [remote-server] [folder-name]`

## Add Remote Server in 
	`git init` / initiliazed repo
	`git remote add [alias] [url]`

## Pull Data - Download source code & merge to current repo
	`git pull [alias-remote-server] [branch-name]`

## New Branch
	`git branch [branch-name]`

## Push Branch
	`git push [alias-remote-server] [branch-name]`
