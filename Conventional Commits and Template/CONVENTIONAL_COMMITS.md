# Welcome to Conventional Commits 1.0.0
![Welcome](https://www.icegif.com/wp-content/uploads/icegif-87.gif) 
-----------------
### Maybe you are asking yourself what are Conventional Commits and why do you need to learn them.
![What is it](https://cdn.dribbble.com/users/60517/screenshots/787426/questions.gif)
### What is a Convetional Commit?
The Conventional Commits specification is a lightweight convention on top of commit messages. It provides an easy set of rules for creating an explicit commit history; which makes it easier to write automated tools on top of.

----------
### Why use Convetional Commit
1. Automatically generating CHANGELOGs.
2. Automatically determining a semantic version bump (based on the types of commits landed).
3. Making it easier for people to contribute to your projects, by allowing them to explore a more structured commit history.
![What is it](https://cdn.dribbble.com/users/2103338/screenshots/7155620/media/65aeca6c38214e96cd6bfedbca9b843e.gif)
---------

### The commit message should be structured as follows:
```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

-------------
### Types
|Type |Definition|
| ------ | ------ |
|fix |a commit of the type fix patches a bug in your codebase|
|feat|a commit of the type feat introduces a new feature to the codebase|
|build|Changes that affect the build system or external dependencies|
|docs|Documentation only changes|
|ci|Changes to our CI configuration files and scripts|
|refactor|A code change that neither fixes a bug nor adds a feature|
|style|Changes that do not affect the meaning of the code|
|test| Adding missing tests or correcting existing tests|
|perf|A code change that improves performance|

-----------
### Scope
The scope should be the name of the npm package affected (as perceived by the person reading the changelog generated from commit messages.

The following is the list of supported scopes:

-animations
-common
-compiler
-compiler-cli
-core
-elements
-forms

------------
### Body 
Just as in the subject, use the imperative, present tense: "change" not "changed" nor "changes". 

-----------
### Footer
footers other than BREAKING CHANGE: <description> may be provided and follow a convention similar to git trailer format.
  
-----------
### Example
![Example](https://jonmgomes.com/wp-content/uploads/2020/03/Liquid-Lightbulb-Animation-V2-800x600-1.gif) 
 
#### Commit message with scope
  ```
  feat(lang): add polish language
  ```
  #### Commit message with no body
  ```
  docs: correct spelling of CHANGELOG
  ```
  #### Commit message with description and breaking change footer
  ```
  feat: allow provided config object to extend other configs

BREAKING CHANGE: `extends` key in config file is now used for extending other config files
  ```

---------
  ## Bibliography
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
-------
 ### Author
  Ivanna Cevallos
  Student Computer Science EPN


