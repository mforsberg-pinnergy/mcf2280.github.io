# Learning Git
### or how I learned to stop worrying and love version control.
---
## Getting Started
---
### Creating a repository
For git to be useful we need to track something.
We will start with an empty directory

```
> mkdir Repository
> cd Repository
> git init
```
Which is equivalent to:
```
> git init Repository
```
The init command can be used on an empty directory or on with files in it. Either way
the files that are going to be tracked must be added to the repository
```
(1)> git add file1.txt

(2)> git add file*.txt

(3)> git add -A .\foo

(4)> git add -A
```
  1. Adding a single file
  2. Adding all files that start with file and end with .txt
  3. Adding all files that are untracked in the foo directory
  4. Adding all untracked files in repository folders

  
