# What is Git?
---
Simply put Git is a distributed version control system. It allows users to navigate to certain places in the history of files (usually plain text documents). A great advantage of Git is its distributive nature. Many if not most commands are local. So you are working with a local copy most of the time, making learning a more forgiving process. Another great thing is most commands are additive in nature meaning that you are **usually** adding information not destroying it.

It is probably best to start with some vocabulary.

**Repository:** A collection of files that are monitored for change and the history of changes at certain points.

**Commit:** (verb) To mark a certain point in the history of the repository. 

**Commit:** (noun) A marked state in the history of the repository.

**Initialize:** Create a repository. This create a .git folder that is used by Git to version the repository.

---
## File Status
A file can have one of four states as far as git is concerned: untracked, unmodified, modified, staged.

**Untracked:** These are files that Git does not know about. Any changes will subsequently not be monitored.

**Unmodified:** These files are monitored by Git. When changes are made Git will denote these files as modified.

**Modified:** These are files that are denoted as "dirty". They have changes that have not been saved to version control. They are not yet set to be saved with the next commit. You can not change branches while you have files in the modified state because that would mean losing the changes that have been made to them.

**Staged:** The group of modified files that are set to be written to version control on the next commit.

---

**Add:** To move a file from untracked to unmodified

**Remove:** To move a file from unmodified to untracked

**Clone:** To make a local copy of a remote repository