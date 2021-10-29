# ***MERGE***

## *Git merge*
The current branch will be updated to reflect the merge, but tha target branch will not be affected at all. Again, this means that ***git merge*** typically used in conjunction with ***git checkout*** to select the current branch and ***git branch -d*** to remove the obsolete target branch. 

![Merge](https://wac-cdn.atlassian.com/dam/jcr:389059a7-214c-46a3-bc52-7781b4730301/hero.svg?cdnVersion=54)

In ***git*** there are two ways that allow us to join branches, ***git merge*** and ***git rebase***. The usual way is ***git merge***, which performs a three way merge between the last two on each branch.
Create a new branch We know him as Checkout. Join two branches we know him as merge.

![Merge2](https://wac-cdn.atlassian.com/dam/jcr:7afd8460-b7bf-4c42-b997-4f5cf24f21e8/01%20Branch-2%20kopiera.png?cdnVersion=50)



 ---

| ***Commands*** | ***Description*** |
| --- | --- |
| git branch | List the branches. |
 |  git branch [name] | Creation of branch. |
| git checkout [name_branch] | Allows the change of branch. | 
| git merge [name_brach] | Union of a branch with another branch.  |
|git branch -d \<nameBranch>|Delete a branch. The branch must be fully merged in its upstream branch or in Head.|
|git branch -D \<nameBranch>|Delete branch without asking.|
|git log|This command is used to list the version history for the current branch.|
|git log --all|Force the log tool display all commits.|
|git log --oneline|Each commit will be shown as simply the commit hash followed by the commit message, on a single line.|
|git log --graph|Display the commit history in an ascii art graphical representation. |
|git log --oneline --graph |See commits as simply with an ascii art graphical representation|
|||

