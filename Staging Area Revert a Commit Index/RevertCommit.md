# Changes to be Commited

## Madelyn Fernandez
![Git Commit](https://www.drupal.org/files/project-images/github_commits_logo.png)

---

## git reset

When we run git commit, a commit is created and the branch pointed to by HEAD is moved,
and when we run git reset it moves back to HEAD ~ (the parent of HEAD), example:
run git reset first_seven_digits_of_commit.
The main branch points to the commit with reference to the first 7 digits.

![Git reset](https://i.stack.imgur.com/qRAte.jpg)

---

### git reset --soft
the last git commit command is rolled back, history record is removed, but stays in stage / index.

### git reset --mixed

remove the last commit and also unstaged everything. Go back to before executing all 
the git add and git commit commands.

From history it is removed to the working Directory.

### git reset --hard

one of the few cases where Git actually destroys the data as it forcibly overwrites the files in the
Directory of Work.
![Git Rest](https://res.cloudinary.com/practicaldev/image/fetch/s--Qwai2otP--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://thepracticaldev.s3.amazonaws.com/i/ykloyhbng2shcjnfvm56.png)

---

## Summary
The reset command overwrites these three trees in a specific order, stopping
when told:
1. Move branch HEAD points to (stop here if --soft)
2. Make the Index look like HEAD (stop here unless --hard)
3. Make the Working Directory look like the Index

> [La guía básica de Git y Github para principiantes](https://medium.com/@sthefany/primeros-pasos-con-github-7d5e0769158c)


