---
layout: post
title:  "My Git Notes"
tags: git 
mathjax: on
---

### Git branch

```console

# show all branchs and your current branch
git branch 

# delete branch
git branch -D ${branch_name}

```

### Git reset

```console

# reset to previous commit id, keep all local changes
git reset --soft ${commit_id}

# reset to previous commit id, will not keep local changes
git reset --hard ${commit_id}

```


### Git cherry-pick
git cherry-pick can be userful for undoing changes. For example, say a commmit is accidentally made to the wrong branch, you can switch to the correct branch and `cherry-pick` the commit to where it should belong.

Example:
Working on production, checkout, commit and push from local prod, not the `origin/prod`. when I create PR, there shows 2 files changes and 2 commits (but should only have one commit).

Solution:


```console

# step 1: get lastest 2 commit ids
git log -2

# step 2: checkout remote prod
git checkout origin prod

# step 3: checkout to a new branch
git checkout -b new_branch 

# step 4: cherry pick your commit by commit_id
git cherry-pick ${commit_id} 


```

