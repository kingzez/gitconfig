# gitconfig
>my git config

```
[core]
	excludesfile = /Users/w/.gitignore_global
[push]
	default = matching
[alias]
	ad = add
	cm = commit
	br = branch
	cl = clone
	di = diff
	dlc = diff --cached HEAD^
	fe = fetch
	l = log
	lo = log --oneline --decorate
	ls = log --pretty=format:"%C(yellow)%h%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate
	lds = log --pretty=format:"%C(yellow)%h\\ %ad%Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --date=format:'%Y-%m-%d %H:%M:%S'
	ld = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
	m = merge
	co = checkout
	s = status
	po = pull
	pu = push
	sl = stash list
	sa = stash apply
	ss = stash save
[log]
	date = format:'%Y-%m-%d %H:%M:%S'

```
