# How to create a template for commits

1. [What is a template?](#topic01)
2. [Create a template](#topic02)
3. [Documentation](#topic03)

## What is a template? <a name="topic01"></a>

<p align="center">
<img src="https://user-images.githubusercontent.com/88261724/139181767-c83f1985-4a4b-4c94-8981-51e9f0a11def.png" width="300px">
</p>

Document or file that contains all the lines, proportions, sizes, typography, structure, colors and indications necessary that allows to orient, port or build, a predefined design or scheme.

## Create a template <a name="topic02"></a>

> The value in creating a custom commit template is that you can use it to remind yourself (or others) of the proper format and style when creating a commit message.

1. We open our terminal and check if there is no previously configured template in the current repository (You can leave out the --global flag if you only plan on using this template for a single, individual repo).

```
git config --global commit.template
```

2. We create a hidden file with the format that our template will have.

```
touch .mytemplate
```

3. We proceed to edit the `.mytemplate` file.

```
vim .mytemplate
```

5. In our case we will use the "_Conventional Commits v1.0.0_" format:

```bash
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

5. We set our new template created by default:

```
git config --global commit.template .mytemplate
```

6. Ready, our template is configured. Now when you make a commit with the `git commit` command, it will display the format that we established.

## Documentation <a name="topic03"></a>

[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

[Using Git Commit Message Templates to Write Better Commit Messages](https://gist.github.com/lisawolderiksen/a7b99d94c92c6671181611be1641c733)

[Create A Custom Git Commit Template](https://alex-wasik.medium.com/create-a-custom-git-commit-template-84468232a459)

[Customizing Git - Git Configuration](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)
