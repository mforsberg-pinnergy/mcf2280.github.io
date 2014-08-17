# Gitting Started
---
## Creating a repository

For git to be useful we need to track something. We will start with an empty directory

	$ mkdir repo
	$ cd repo
	$ git init


Which is equivalent to:

	$ git init Repository

The init command can be used on an empty directory or on with files in it. Either way
the files that are going to be tracked must be added to the repository

---
	$ git add file1.txt 

Adding a single file

	$ git add file*.txt

Adding all files that start with file and end with .txt

 	$ git add -A .\foo

Adding all files that are untracked in the foo directory

	$ git add -A

Adding all untracked files in repository folders