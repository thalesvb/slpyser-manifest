slpyser manifest (git-repo tool)
===

This repository contains the [git-repo][1] xml manifest to join the whole slpyser project, necessary to run unit tests.
If you just want to use the libray, you can directly fetch the slpyser repository.

This was mainly created to use in TravisCI / unit testing.

Initialize & Sync in a nutshell
---

repo init -u https://github.com/thalesvb/slpyser-manifest.git
repo sync

[1]: https://code.google.com/p/git-repo/
