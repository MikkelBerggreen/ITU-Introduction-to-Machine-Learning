# IAML material
This repository contains the relevant material for solving the exercises and assignments in the IAML course. 
The repository is regularly updated with new content and possibly changes (important changes will be announced). 
Exercise solutions will also be uploaded here approximately one week after the week of a given exercise.

## Suggested usage
We suggest you fork this repository to your own Github account and use it as a repository for your solutions. This makes it easy for you to fetch new updates from this repository.

You may use the following guide to create your own fork of this repository, clone it to your local machine, and add this repository as an additional remote:

1. Fork the repository to your own account using the button on Github.
2. Clone the forked repository to your computer with the command `git clone git@github.itu.dk:<user>/material.git` where `<user>` is your username (ITU initials).
3. Navigate to the newly cloned repository.
4. Add the original repository as a remote using the following command `git remote add upstream git@github.itu.dk:IAML/material.git`. 

This process results in your local repository having two remotes: `origin` and `upstream`. Whenever you want to push changes to your own repository, use the `origin` remote.

When you want to pull updates from the source IAML repository into your local clone, perform the following actions:

1. Fetch the latest changes from the upstream repository using: `git fetch upstream`.
2. Merge the changes into your local branch: `git merge upstream/master`.
3. Resolve any conflicts using your method of choice (we try to keep conflicts to a minimum).

### Required git setup
You need both `git` and `git-lfs` installed to use the repository directly. You may find up to date information on how to install these at:
* `git`: [installation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* `git-lfs`: [installation guide](https://git-lfs.github.com/)

## Alternatives
If you really don't like git, we also provide regularly updated zip releases of the repository contents. 