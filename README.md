vdemeester-gitolite-local-code
==============================

My addition to gitolite than can be added as local-code in the gitolite-admin repo, based on http://sitaramc.github.com/gitolite/cust.html#pushcode documentation.

This is the alternative as using a branch of a gitolite-clone, and is especially useful if gitolite has been installed using package manager (or in a non _local_ way).

## Using it

The idea is to use the _subtree_ feature of recent git version (or the git-subtree tool) to add and update this code in the actual ``gitolite-admin`` repository.