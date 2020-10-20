# README

## Recipes for Contributing (GitHub Users)

1.) Fork the [repository](https://github.com/manyaagarwal/particlesilo).

```
git clone git@github.com:uzzielperez/particlesilo.git 
# or replace uzzielperez with your user name

cd particlesilo
git remote add upstream git@github.com:cms-exotica-diphotons/diphoton-analysis.git
git checkout master
git pull upstream master # pull latest from master
 
# check diff
git diff -U0 --color remotes/upstream/master
 
# to reset to main 
git reset --hard upstream/master

# to push changes to master 
git push origin master

```
When ready, submit a Pull Request. :) 

## Contact Us for Contributions


