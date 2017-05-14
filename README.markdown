Perl scripts for setting up and using a git mirror. See [Git](http://wiki.gnucash.org/wiki/Git) in the Gnucash Wiki and the embedded documentation for more information.

**Note** while thise scripts were created by the Gnucash project to maintain a git mirror of its svn repository,
they are no longer in use by the project. Gnucash has completely migrated to git since then. The scripts are
kept available as they are as they may be useful to other projects. They aren't maintained any more though.


* git-svn-mirror: Set up and maintain a git mirror of a Subversion repository

* git-update: Use this instead of git pull --rebase to update your working copy of a mirrored repository; it ensures that your local references are in sync so that you can safely git svn dcommit back to the subversion repository.
