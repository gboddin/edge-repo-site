---
layout: page
permalink: /
---
_Edge Repo is a Yum RPM repository for most major RPM distributions (Redhat and Fedora)_

It tries to stay as close as possible to upstream releases version


#### Packages included (non-exhaustive) :

* Apache 2.4
* PHP 5.6
* Varnish 4.1
* Redis 3.2
* ...


#### Supported distribution :

* CentOS/RHEL/OCL/SL 6 (el6)
* CentOS/RHEL/OCL/SL 7 (el7)
* Fedora 23
* Fedora 24


#### GPG

The GPG key is available at [http://repo.siwhine.net/EDGE-REPO-KEY.pub](http://repo.siwhine.net/EDGE-REPO-KEY.pub)

#### Package updates

This repository is directly connected to the repo. 
Once the compilations are successful, the RPMs are automatically deployed to the repository.
The compilations are triggered on travis-ci by branch name.

#### Contribution

Any pull-request to the [project](https://github.com/gboddin/edge-repo) is welcome just make sure you pick the right branch to work on.

#### Addition

We won't add software on request, but feel free to add it yourself by creating a PR.
