# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [x] Create your own version of this repo - Fork
- [x] Add your PM as a collaborator
- [x] Clone this repo
- [x] Create a branch `git checkout -b 'firstName-lastName'`
  - [x] Add a file to the project called `yourFirstName-yourLastName`.txt. This file can contain anything.
  - [x] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [x] Create a Pull-Request to submit your work
  - [x] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [x] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
Go back and follow the same steps for your [UI-III-Flexbox project](https://github.com/LambdaSchool/UI-III-Flexbox) and your [User Interface - Great Idea Project](https://github.com/LambdaSchool/User-Interface).

In order to do this, you **do not** need to create new forks of these projects. Follow the steps below for each project:

- [ ] Add your PM as a collaborator to your fork. 
- [ ] Go into your project folder, make a new branch `firstname-lastname`
- [ ] Add your first and last name to the README.md file in the project and save.
- [ ] add/commit/and push to your own branch  **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Stretch
- [x] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.
  - [x] Research and understand what a `merge conflict` is and how to resolve it.
        #Per GitHub help, merge conflicts happen when branches that have competing commits are merged, and Git needs help to decide which changes to incorporate in the final merge. All merge conflicts must be resolved before a pull request can be merged on GitHub. 
        #To resolve a merge conflict, one would need to manually edit the conflicted file to select the changes to keep in the final merge. This can be done by either: 1. Resolving the conflict on GitHub using the conflict editor, or 2. Resolving the conflict on the command line
  - [x] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
        #git pull is used to fetch and download content from a remote repository and merge the remote content and heads into a new local merge commit (it is a combination of git fetch and git merge).
        #git merge is used to take the independent lines of development created by git branch and integrate them into a single branch.
        #git rebase is used to change the base of the branch from 1 commit to another (but should not rebase commits once they have been pushed to a public repository)
  - [x] Reseach the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and ammends previous commits you have made.
        #git clean is used to remove untracked files from the current branch
        #git revert is used to invert the changes introduced by a specified commit (by creating a new commit that reverts the effects of the specified commit)
        #git reset is used to roll back to a previous commit state (--soft: move HEAD pointer but no changes on index and working directory; --mixed: move the HEAD pointer and update the staging area; --hard: move the HEAD pointer, update the staging area, update the working directory to match the staging area)
- [x] Research and set up a Graphical User Interface (GUI) Git console. 

- [x] Research and setup SSH keys with Github, so that you do not need to input your username/password each time you push. 

