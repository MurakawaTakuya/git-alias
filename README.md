# git-alias

## alias list
```
all: config --global alias.all "config --get-regexp ^alias\."
st: status
ad: !sh -c "git add . && git status"
co: checkout
cm: commit -m
cma: commit --amend
cmf: commit --fixup
br: branch
lo: log --oneline
fe: fetch
ps: push
psf: push --force--with-lease
pl: pull
plm: pull origin main
plo: pull origin
sh: stash
shp: stash pop
shl: stash list
sw: switch
swc: switch -c
swm: switch main
rb: rebase
rbi: rebase -i
rbm: rebase main
rs: reset
rss: reset --soft
rsh: reset --hard
df: diff
cp: cherry-pick
```

## alias command list
```
git config --global alias.all "config --get-regexp ^alias\."
git config --global alias.st 'status'
git config --global alias.ad '!sh -c "git add . && git status"'
git config --global alias.co 'checkout'
git config --global alias.cm 'commit -m'
git config --global alias.cma 'commit --amend'
git config --global alias.cmf 'commit --fixup'
git config --global alias.br 'branch'
git config --global alias.lo 'log --oneline'
git config --global alias.fe 'fetch'
git config --global alias.ps 'push'
git config --global alias.psf 'push --force-with-lease'
git config --global alias.pl 'pull'
git config --global alias.plm 'pull origin main'
git config --global alias.plo 'pull origin'
git config --global alias.sh 'stash'
git config --global alias.shp 'stash pop'
git config --global alias.shl 'stash list'
git config --global alias.sw 'switch'
git config --global alias.swc 'switch -c'
git config --global alias.swm 'switch main'
git config --global alias.rb 'rebase'
git config --global alias.rbi 'rebase -i'
git config --global alias.rbm 'rebase main'
git config --global alias.rs 'reset'
git config --global alias.rss 'reset --soft'
git config --global alias.rsh 'reset --hard'
git config --global alias.df 'diff'
git config --global alias.cp 'cherry-pick'
```

## alias deletion
(例えばpsを無くしたい場合)
```
git config --global --unset alias.ps
```
