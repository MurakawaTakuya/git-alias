# git-alias

## 使用可能なコマンドのリスト
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
fp: !sh -c "git fetch && git pull"
ps: push
psf: push --force--with-lease
pl: pull
plm: pull origin main
plo: pull origin
sh: stash -u
shp: stash pop
sha: stash apply
shl: stash list
sw: switch
swc: switch -c
swm: switch main
rb: rebase
rba: rebase --abort
rbc: rebase --continue
rbi: rebase -i --autosquash
rbm: rebase main
rs: reset
rss: reset --soft
rsh: reset --hard
df: diff
cp: cherry-pick
```

## エイリアスの設定
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
git config --global alias.fp '!sh -c "git fetch && git pull"'
git config --global alias.ps 'push'
git config --global alias.psf 'push --force-with-lease'
git config --global alias.pl 'pull'
git config --global alias.plm 'pull origin main'
git config --global alias.plo 'pull origin'
git config --global alias.sh 'stash -u'
git config --global alias.shp 'stash pop'
git config --global alias.sha 'stash apply'
git config --global alias.shl 'stash list'
git config --global alias.sw 'switch'
git config --global alias.swc 'switch -c'
git config --global alias.swm 'switch main'
git config --global alias.rb 'rebase'
git config --global alias.rba 'rebase --abort'
git config --global alias.rbc 'rebase --continue'
git config --global alias.rbi 'rebase -i --autosquash'
git config --global alias.rbm 'rebase main'
git config --global alias.rs 'reset'
git config --global alias.rss 'reset --soft'
git config --global alias.rsh 'reset --hard'
git config --global alias.df 'diff'
git config --global alias.cp 'cherry-pick'
```

## エイリアスの削除
(例えばpsを無くしたい場合)
```
git config --global --unset alias.ps
```
