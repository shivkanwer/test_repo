# Git for professionals

## The perfect commit

- Add the right changes
- Compose a good commit message
  1. Subject - Concise summary of what happened
  2. Body - more detailed explanation
     - What is now different than before?
     - What is the reason for the change?
     - Is there anything to watch out for / anything remarkable?
- Make use of staging are to commit selective changes/files
- Do not commit all changes at once
- Only combine changes from one topic into a single commit

## Branching strategies

- Agree on branching workflow in your team
- Create a written convention
- State (Dev, Test, Prod) branches, Release branches, Feature branches, Hot fix branches
- Types of branches:
  - **Long-running branches** that exist throughout the complete lifetime of the project [e.g. main, dev, uat etc.]
  - **Short-lived branches** are typically created for bug fixes, feature, experiments etc. and are deleted after integration (merge/rebase) with long running branch.
- Many teams prohibit direct commits to the long-running branches, commits to these branches can only be made through a merge or a rebase

## Pull Requests

- Pull requests are used for communicating the changes and reviewing those changes.
- Pull request is also a way to contribute to repositories which you don't have direct access to [e.g. open-source projects]
- Fork is a personally copy of your git repository

## Merge Conflicts

- Merge conflicts occur when you merge changes from a different source
  E.g.
  - A file is deleted in one branch but modified in another
  - Same line of code changed in two branches so git does not know which change to keep

## Merge vs Rebase
