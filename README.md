# nginx
This is a fork of the original nginx repository.   This repository should only merge changes from the original fork based on release commits and not the master branch.

## nginx-upstream-dynamic-servers
This repository also includes niginx-upstream-dynamic-servers [Github](https://github.com/GUI/nginx-upstream-dynamic-servers).  We will maintain updates to this code from possibly other forks as they are more up to date.   This module adds a nginx plus feature known as dns resolver for upstreams.  Normally NGINX does a DNS lookup once at startup and never looks them up again.  This feature is part of the NGINX Plus but the license costs ~1500 per server.  So this module is an open source solution to add this feature.

## NOTE:
1. The main reason for our maintaining a custom fork is to have the ability to compile in custom modules during compile time that are not available in the main line releases.   This project also includes a way to cross compile windows binaries on linux in lieu of the new jenkins build and deploy platform.
