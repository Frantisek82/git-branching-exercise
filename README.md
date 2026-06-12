# Git Branching Exercise

A hands-on Git project demonstrating professional branching workflows, merge strategies, hotfix handling, conflict resolution, and repository restructuring.

## Overview

This repository was created as part of a Git workflow exercise simulating the development of a fictional online learning platform called **CodeForTheSpace**.

The goal was not to build software, but to learn how real development teams use Git to manage features, releases, hotfixes, and refactoring.

## Git Concepts Demonstrated

* Repository initialization
* Feature branches
* Development and production branches
* Fast-forward merges
* Merge commits
* Merge conflict resolution
* Hotfix workflows
* Refactoring using `git mv`
* Branch visualization with Git graphs

## Branches Used

* master
* develop
* feat-courses
* feat-landing
* feat-logic
* refactor-restructuring
* hotfix-login
* fix-landing-page-styles
* feat-payment-gateway

## Key Learning Outcomes

During this exercise I learned how to:

1. Isolate work using feature branches.
2. Merge completed features into a development branch.
3. Release changes into production.
4. Create emergency hotfixes directly from production.
5. Resolve merge conflicts manually.
6. Visualize and understand Git history using commit graphs.

## Useful Commands

View branch history:

git log --graph --oneline --all --decorate

View repository status:

git status

List branches:

git branch

Switch branches:

git checkout branch-name

Create a new branch:

git checkout -b branch-name

Merge a branch:

git merge branch-name

## Project Structure

courses/
landing/
logic/
payment/

## Author

Created as a Git learning exercise demonstrating practical version control workflows.

