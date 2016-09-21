---
layout: page
permalink: /
---
_Edge Repo is a Yum RPM repository for EL distributions (6 and 7)_

It tries to stay as close as possible to upstream releases version


## Packages included (non-exhaustive) :

* Apache 2.4
* PHP 5.6
* Varnish 5.0
* Redis 3.2
* ...


## Supported distribution :

* CentOS/RHEL/OCL/SL 6 (el6)
* CentOS/RHEL/OCL/SL 7 (el7)


## Proof of build

_It might be important for some people to see the build.log of the packages they will use._

* #### Travis-ci

We use travis-ci's public infrastructure to build the packages on commit and deploy them to the repo.

* #### Logs

Build logs can all be found on travis-ci : [https://travis-ci.org/gboddin/edge-repo/branches](https://travis-ci.org/gboddin/edge-repo/branches)

* #### Build tools

The tools used to build the packages can all be found at (https://github.com/gboddin/edge-repo).

## Other informations

### GPG

The GPG key is available at [http://repo.siwhine.net/EDGE-REPO-KEY.pub](http://repo.siwhine.net/EDGE-REPO-KEY.pub)

### Package updates

This repository is directly connected to the repo. 
Once the compilations are successful, the RPMs are automatically deployed to the repository.
The compilations are triggered on travis-ci by branch name.

### Contribution

Any pull-request to the [project](https://github.com/gboddin/edge-repo) is welcome just make sure you pick the right branch to work on.

### Addition

We won't add software on request, but feel free to add it yourself by creating a PR.
