# Gitting Started
---
## Git Command Line

We will ultimately be using a Git GUI, but we are going to start off on the command line for a multitude of reasons. 

* There are many different GUIs and each has its own way of doing things, many with multiple ways of doing the same thing. The command line shows how things are done at a base level without obscuring too much detail.

* The Git commands comprise the vocabulary that we will use to talk about operation that are performed in all instances of Git.

* It is easier to demonstrate the narrative through words than mouse clicks

## Creating a Repository

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