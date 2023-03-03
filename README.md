# ALX Pre Course

Welcome to the ALX Pre Course repository! This project is part of the pre-course work for the ALX Software Engineering program. The main objective of this project is to teach you how to use Git, a popular version control system used in software development.

By completing this project, you will learn the basics of Git, including creating a repository, committing changes, branching, merging, and collaborating with others. You will also learn how to write good README files, an essential part of any project.

Throughout this project, you will be working with the command line to perform various Git operations, so you will get hands-on experience with the tool. The project assumes no prior knowledge of Git, so anyone can follow along and learn.

Whether you are a beginner or an experienced developer, this project will provide you with valuable skills that you can use in your future projects. So, let's get started and learn Git!


## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

* What is source code management
* What is Git
* What is GitHub
* What is the difference between Git and GitHub
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code
* How to pull updates
* How to create a branch
* How to merge branches
* How to work as collaborators on a project
* Which files should and which files should not appear in your repo.

## Requirements
To complete this project, you will need to:

* Create a GitHub account (if you don't already have one)
* Create a personal access token on GitHub
* Update your profile on the ALX Intranet with your GitHub username
* Create a new repository called "alx-pre_course" on GitHub
* Clone the repository to your local machine
* Create a README.md file and add it to your repository
* Add and commit changes to your repository
* Push your changes to GitHub
* Work with branches and merge changes
* Collaborate with others on a project

Note that you should use the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.


## Tasks
0. Create and setup your Git and GitHub account

* Create an account on GitHub (if you don't already have one)
* Create a Personal Access Token on GitHub
* Update your profile on the Intranet
* Create your first repository
* Clone your repository
* Create the README.md and push the modifications

1 Repo-session

* Create a new directory called `0x01-git` in your `alx-pre_course` repo
* Include a non-empty README.md in your `0x01-git` directory
* Commit and push your code to GitHub

2 Coding fury road

* Create the following directories at the root of your project: `bash`, `c`, `js`
* Create the following empty files:
* `c/c_is_fun.c`
* `js/main.js`
* `js/index.js`
* Create a file `bash/alx` with the following two lines inside:
* ```#!/bin/bash```
* ```echo "ALX"```
* Create a file `bash/school` with the following two lines inside:
*`#!/bin/bash`
* `echo "School"`
* Add all these new files to Git
* Commit your changes (message: "Starting to code today, so cool") and push to the remote server

3 Collaboration is the base of a company

* Create a branch named `update_script`
* In the file `bash/alx`, change "ALX" to "ALX School"
* In the file bash/school, change "School" to "The school is open"
* Add and commit these changes (message: "My personal work")
* Push the changes to the `update_script` branch on GitHub
* Open a pull request and merge your changes to the `main` branch

4 Never push too much

* Create a .gitignore file in the root of the repository
* Add `~*` to the .gitignore file
* Add all the files that match this pattern to Git
* Commit your changes (message: "Never push too much") and push to the remote server

4 Collaboration: be up to date

* From the `main` branch, create a new branch named `up_to_date`
* In the file `bash/alx`, change "ALX School" to "ALX School, a new school"
* Add and commit this change (message: "How to be up to date in git")
* From the update_script branch, merge the branch up_to_date
* Resolve the conflicts (choose "ALX School, a new school")
* Commit your changes (message: "Merge branch 'up_to_date', fix conflicts") and push to the remote server

5 Merge

* From the `update_script` branch, merge the `main` branch
Resolve the conflicts (choose "ALX School, a new school" and "The school is open")
Commit your changes (message: "Merge branch 'main' into update_script") and push to the remote server
From the `main` branch, delete the `update_script` branch
Technical writing

Write a technical blog post that explains Git to a non-technical person
Publish your blog post on LinkedIn


