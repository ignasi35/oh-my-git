A collection of git scripts that I use to automate my workflow

## Requirements

Some commands requires extra libraries, namely `hub` and `jq`. 

* `hub`  - https://hub.github.com/
* `jq` - https://stedolan.github.io/jq/

## Install

### Check out this repo

```
git clone git@github.com:renatocaval/oh-my-git.git
```

* Add the bin folder to your PATH
* source `git-functions.sh` and `gh-functions.sh`
* define env variable: `GITHUB_SRC` (eg: GITHUB_SRC=/Users/renato)
* define env variable: `GITHUB_USER` (eg: GITHUB_USER=renatocaval)


### pr.new

The commant `pr.new` doesn't work if your git editor is set to `vim`. 
You will get the following error message: `Vim: Warning: Output is not to a terminal`. 

To use that command you will need to switch to another editor: VS Code and Emacs are know to work.