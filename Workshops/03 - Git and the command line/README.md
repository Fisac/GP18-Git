# 03 - Git and the command line

[<img src="https://i.giphy.com/l46C6sdSa5DVSJnLG.gif" alt="02 - Version Control" width="100%">](https://git-scm.com)

Today we're going to continue learning version control with [Git](https://git-scm.com) - but this time we will make all the magic happen from the [command-line](https://en.m.wikipedia.org/wiki/Command-line_interface).

> [Git](https://en.m.wikipedia.org/wiki/Git) is a [version control](https://en.m.wikipedia.org/wiki/Version_control) system that is used for software development and other version control tasks. As a [distributed revision control](https://en.m.wikipedia.org/wiki/Distributed_version_control) system it is aimed at speed, data integrity, and support for distributed, non-linear workflows.

### Commands

Command | Description
------- | -----------
[`git add`](https://tldr.ostera.io/git-add) | Adds changed files to the index.
[`git branch`](https://tldr.ostera.io/git-branch) | Main git command for working with branches.
[`git checkout`](https://tldr.ostera.io/git-checkout) | Checkout a branch or paths to the working tree.
[`git clone`](https://tldr.ostera.io/git-clone) | Clone an existing repository.
[`git commit`](https://tldr.ostera.io/git-commit) | Commit staged files to the repository.
[`git init`](https://tldr.ostera.io/git-init) | Initializes a new local Git repository.
[`git log`](https://tldr.ostera.io/git-log) | Show a history of commits.
[`git merge`](https://tldr.ostera.io/git-merge) | Merge branches.
[`git pull`](https://tldr.ostera.io/git-pull) | Fetch branch from a remote repository and merge it to local repository.
[`git push`](https://tldr.ostera.io/git-push) | Push commits to a remote repository.
[`git reset [file]`](https://tldr.ostera.io/git-status) | Unstage a file, but preserve its contents.
[`git status`](https://tldr.ostera.io/git-status) | Show the index (changed files).

## Installation

If you're running Windows you can [visit the official Git website](https://git-scm.com/downloads) to get started.

If you're running macOS you've to install the Xcode command line tools to get started:

```bash
$ xcode-select --install
```

## Assignments

1. [Create a new directory](https://tldr.ostera.io/mkdir) on your computer, [`cd`](https://tldr.ostera.io/cd) into it and run [`git init`](https://tldr.ostera.io/git-init) to initialize a new Git repository.

2. [Create](https://tldr.ostera.io/touch) a [`README.md`](https://yrgo.github.io/languages/markdown) file in the repository and add a title to the document.

    > :zap: **Tip**: You can run [`git status`](https://git-scm.com/docs/git-status) to view the status of your files.

3. Now [add](https://tldr.ostera.io/git-add) and [commit](https://tldr.ostera.io/git-commit) the newly created `README.md` file.

4. Go to GitHub and [create an empty repository](https://help.github.com/articles/create-a-repo/). Do **not** initialize the repo with a `README` or add `.gitignore` and `license` files.

5. [Connect](https://help.github.com/articles/adding-a-remote/) your local repo with the newly created GitHub repo and [push](https://tldr.ostera.io/git-push) your files.

    > :zap: **Tip**: The first time you push to a [remote](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes) repo, you need to run `git push -u origin master` to set the remote branch as default upstream branch for future pushes/pulls. `-u` is shorthand for `--set-upstream`.

6. Create a new [branch](https://tldr.ostera.io/git-branch) and name it `feature`.

7. [Checkout](https://tldr.ostera.io/git-checkout) the `feature` branch.

8. Create a new file, name it `LICENSE` and fill it with the [MIT license](https://en.m.wikipedia.org/wiki/MIT_License#License_terms).

9. [Add](https://tldr.ostera.io/git-add) and [commit](https://tldr.ostera.io/git-commit) the `LICENSE` file.

    > :zap: **Tip**: You can now compare and see the differences between the two branches in your file explorer.

10. Checkout the `master` branch and [merge](https://tldr.ostera.io/git-merge) it with the `feature` branch.

11. [Delete](https://tldr.ostera.io/git-branch) the `feature` branch with the `-d` flag.

12. [Push](https://tldr.ostera.io/git-push) your master branch to GitHub.

13. Create a new [branch](https://tldr.ostera.io/git-branch) and give it a suitable name. [Checkout](https://tldr.ostera.io/git-checkout) the new branch.

14. Add a `.gitignore` file and fill it with the [Unity .gitignore template](https://github.com/github/gitignore).

15. [Add](https://tldr.ostera.io/git-add) and [commit](https://tldr.ostera.io/git-commit) the `.gitignore` file.

16. Try to [push](https://tldr.ostera.io/git-push) the new branch to GitHub. You will now be prompted with an error message asking you to set an upstream branch. Follow the instuctions and push your changes to GitHub.

17. Merge the branch with master branch on GitHub with a [pull requests](https://help.github.com/articles/about-pull-requests/).

## Extra

1. Give us your best video game tip by contributing to [this list](https://github.com/Fisac/List-of-games).

## Resources

- [Connecting to GitHub with SSH](https://help.github.com/articles/connecting-to-github-with-ssh/) -GitHub Help
- [A Successful Git Branching Model](http://nvie.com/posts/a-successful-git-branching-model) - Vincent Driessen
- [Documentation](https://git-scm.com) - Git
- [Getting Started](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics) - Git
- [Git From the Inside Out](https://codewords.recurse.com/issues/two/git-from-the-inside-out) - Code Words
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit) - Chris Beams
- [Oh shit, git!](http://ohshitgit.com) - Katie Sylor-Miller
- [Open Source Guides](https://opensource.guide) - GitHub
- [A collection of useful Git tips](https://github.com/git-tips/tips) - Git-tips
- [How to keep a fork up to date with the forked repo](https://gist.github.com/CristinaSolana/1885435) - Cristina Solana
