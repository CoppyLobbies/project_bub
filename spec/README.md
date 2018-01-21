# Project Bub
A personal website project.

## Overview
This document contains the process that will be used to develop code for the application as well as the requirements needed to be completed for this project to be complete.

## Development Cycle

To make the development of this project easy, a simple cycle will be used that will use `git` and __GitHub__ to complete.

### Step 0 - Create Issues
Create the *Issues* in __GitHub__ so that work can be complete.  This will be done by me so I can help with the flow of the project.  This will also allow you to code more and think about the work less.

### Step 1 - Pick an Issue
Pick an *Issue* from __GitHub__ to work on and create a new local branch.
```bash
git branch -b <branch_name>
```
The `<branch_name>` should include your initials, the issue number, and a shorthand description as follows:
```bash
<initials>/<issue_number>-<shorthand_desc>

Example:
tr/1-create-spec
```

### Step 2 - Do the work
Complete the work the is described in the description of the *Issue* that you are currently working on.  Make sure that you do not do more work than the ticket describes.  If you are unsure if something is within the "scope" of the ticket, just ask.

### Step 3 - Push the code
Once the work for the ticket is complete locally on your machine, `push` it to __GitHub__
```bash
git push
```
If it is the first time you are `push`-ing your branch to __GitHub__ you may need to also set the `upstream`.  Your terminal will give you instructions on how to do so but if you have trouble, just ask.

__Make sure that you are not `push`-ing to the `master` branch and only to the branch create for the issue.__

### Step 4 - Start Code review
Once you have pushed your code to __GitHub__, create a *Pull Request* in __GitHub__ to request that I review your work.  Once you have done that, send me the link to the PR (*Pull Request*).  

When you create the *Pull Request*, in the description make sure to include 

### Step 5 - Resolve Code Review comments
If there are any changes that need to be made for the PR, I will comment about them with direction on how to fix them in the PR.  Feel free to ask questions on why and/or what needs to be done.

You will need to update your local repository and `push` the changes for the fixes to __GitHub__ similar to Step 3, however you will need to make sure that you are on the same branch that the PR is for.

Once all of the comments in the PR are resolved, merging the branch to master is ready to happen.

### Step 6 - Merge to Master
Click the *Merge* button in the PR (in __GitHub__) to merge the branch to master.  This will add all of your changes to the master branch and complete work on the current ticket.


