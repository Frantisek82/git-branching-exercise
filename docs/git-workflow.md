# Git Workflow Documentation

## Branch Strategy

The project uses two permanent branches:

master
└── Production-ready code

develop
└── Integration branch for completed features

Feature development occurs in dedicated branches.

## Feature Workflow

1. Create feature branch from develop.
2. Implement changes.
3. Commit work.
4. Merge feature into develop.
5. Release develop into master.

Example:

develop
└── feat-courses

develop
└── feat-landing

develop
└── feat-logic

## Hotfix Workflow

When a production issue occurs:

1. Create hotfix branch from master.
2. Implement fix.
3. Merge into master.
4. Merge back into active development branches.

Example:

master
└── hotfix-login

This ensures production issues are fixed without deploying unfinished features.

## Refactoring Workflow

Structural changes are isolated in dedicated branches.

Example:

develop
└── refactor-restructuring

This branch reorganized files using:

git mv

allowing Git to track file movement cleanly.

## Merge Conflict Resolution

A merge conflict occurred while integrating:

* Improve video logic
* Production login fix

The conflict was manually resolved by preserving both sets of changes and creating a merge commit.

## Useful Git Graph Command

git log --graph --oneline --all --decorate

This command provides a visual representation of branch history and merge relationships.
