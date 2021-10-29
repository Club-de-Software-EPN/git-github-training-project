# ***MERGE TYPES***

Git provides various methods to merge different commits into a base commit, we have two main methods:

* Fast Forward
* 3-way


---
---
## *FAST FORWARD MERGE*

> A fast forward merge may happen when there is a linear process from the end of the current branch to the target branch. Instead of “actually” merging the branches, all Git has to do to integrate the histories is move the end of the current branch to the end of the target branch.

![Fast forward explication](https://wac-cdn.atlassian.com/dam/jcr:d90f2536-7951-4e5e-ab79-f45a502fb4c8/03-04%20Fast%20forward%20merge.svg?cdnVersion=45)



---
---

## *3-WAY MERGE*

> 3-way merges use a specific commit to join two histories. This merge gets its name from the fact that Git uses three commits to generate the merge commit: the two ends of the branch and its common predecessor.

![3-way representation](https://wac-cdn.atlassian.com/dam/jcr:91aece4a-8fa0-4fc3-bae9-69d51932f104/05-06%20Fast%20forward%20merge.svg?cdnVersion=45)

