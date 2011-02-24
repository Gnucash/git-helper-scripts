Perl scripts for setting up and using a git mirror. See [Git](http://wiki.gnucash.org/wiki/Git) in the Gnucash Wiki and the embedded documentation for more information.

* git-svn-mirror: Set up and maintain a git mirror of a Subversion repository

* git-update: Use this instead of git pull --rebase to update your working copy of a mirrored repositooy; it ensures that your local references are in sync so that you can safely git svn dcommit back to the subversion repository.
