# Learning about git and github

# git

- git is software...

# github

- It is service provider.

## Description

- track filesfiles

### Termology

- `Repo`,

## Command

- git --version
- git status
- git init : initialized to track and create .git hidden folder.
- git commit : check point ( write -> Add -> Commit)
- git commit -am "update main webseite" : add and commit at same time.

- git log : see all commit
- git log --oneline : see one line commit
  -- working Dir -> git add -> staging Area -> git commit -> Repo -> git push -> github
- git config --global core.editor "code --wait";

- git branch `e.g : master, main, `
- git branch "...";
- git checkout / switch "..."
- git checkout -b pink-mode
- git switch -c dark-mode
- git merge ".." -m "message"
- git brach -d ".." : delete branch
- git diff --staged : differ between A and A at time periods;
- git stash : it used when change the branch when not commiting or still in stagging state.
- git stash pop : it is used to get stash changes.
- git stash list
- git stash apply

  -- git diff 88de311..ca692cd
  -- git diff master slave

- ## git rebase `It used in branch`

  -- git rebase master / main
  -- git rebase --continue : for previous conflicts rebase.

  - git clone <URL>
  - git config --global user.name "Abhijit1102"
  - git config --global user.email "abhijitrajkumar2@gmail.com"

## More command

- git checkout <hash> : detach head
- git checkout 2ef15f3 -> moving back
- git checkout 'master' or git reflog (prev)
- git switch main : re-attach head
- git checkout HEAD~2 : look at 2 commit prior
- git restore filename : get back to last commit version.

## git symbols

- a -> file1 & b -> file2
- ---- : a , ++++ : b in indicates changes in file;

# Remote

- git remote -v
- git remote add origin <URL>
- git push -u origin main [means `origin` to `main`] `-u`: upstream to make stream
- git remote rename oldname newname
- git remote remove name

- git push <remote> <branch>
- git push origin main
- git push <remote> local-Branch : remote-branch
- git fetch & pull : from remote(fetch : get into but dom,t put in working area, pull: get info & add in my working area)

- git pull = git fetch + git merge
- git pull origin main (change will be merged to main)

## feature of github

- Adding collabaration
- codespace
