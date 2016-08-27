---
layout: page
title: Contribute
permalink: /development/
---

## How-to steps :

* ### Fork the repoistory

Go github and fork [https://github.com/gboddin/edge-repo-dev](https://github.com/gboddin/edge-repo-dev).

* ### Clone your fork

```
git clone git@github.com:<username>/edge-repo-dev.git
```

* ### Switch to the branch you want to work on

```
git checkout <package>
```

If you want to propose a new package, use :

```
git checkout -b <package>
```

* ### Work on your repo and push your changes

```sh
# edit SPECS/<package>.spec
# edit SOURCES/<package>/*
# edit SOURCES/<package>.env
git commit
git push
```

* ### Open a pull request
 
With [https://github.com/gboddin/edge-repo-dev](https://github.com/gboddin/edge-repo-dev) as a target repo.

If you're creating a new package, please open an issue so we create a new branch for you to merge to.

* ### Check your build output
 
Go to [https://travis-ci.org/gboddin/edge-repo-dev/branches](https://travis-ci.org/gboddin/edge-repo-dev/branches) and check your build output on the various distributions.

* ### Squash your commits

If building a big package, you will often have to fix issues for specific distribution, leading to a lot of commits when relying on Travis for the tests.

Please squash your commits as much as possible with : `git rebase -i HEAD~<commit count>`

* ### Wait for approval

Drop us a word on the pull request when you're ready. 

We will review your contribution soon ! 
