---
layout: post
title:  "My Git Notes"
tags: git 
mathjax: on
---

git cherry-pick can be userful for undoing changes. For example, say a commmit is accidentally made to the wrong branch, you can switch to the correct branch and `cherry-pick` the commit to where it should belong.

Example:
Working on production, checkout, commit and push from local prod, not the `origin/prod`. when I create PR, there shows 2 files changes and 2 commits (but should only have one commit).

Solution:


```shell

git log -2 # get lastest 2 commits id
git checkout origin prod # checkout remote prod
git checkout -b new_branch # checkout to a new branch
git cherry-pick ${commit_id} # cherry pick your commit id (step 1)


```

