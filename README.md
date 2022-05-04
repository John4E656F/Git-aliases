
# Git Aliases
To make aliases permanent, we have to set them in a file that’s read when you open Terminal. Some common ones are ~/.bashrc and ~/.bash_profile. For this example, let’s use ~/.bash_profile.

From the command line, open to edit the file by running the following:

nano ~/.bash_profile or nano ~/.bashrc

alias ga='git add' <br>
alias gaa='git add .' <br>
alias gaaa='git add --all' <br>
alias gau='git add --update' <br>
alias gb='git branch' <br>
alias gbd='git branch --delete ' <br>
alias gc='git commit' <br>
alias gcl='git clone' <br>
alias gcm='git commit --message' <br>
alias gcf='git commit --fixup' <br>
alias gco='git checkout' <br>
alias gcob='git checkout -b' <br>
alias gcom='git checkout master' <br>
alias gcos='git checkout staging' <br>
alias gcod='git checkout develop' <br>
alias gd='git diff' <br>
alias gda='git diff HEAD' <br>
alias gi='git init' <br>
alias glg='git log --graph --oneline --decorate --all' <br>
alias gld='git log --pretty=format:"%h %ad %s" --date=short --all' <br>
alias gm='git merge --no-ff' <br>
alias gma='git merge --abort' <br>
alias gmc='git merge --continue' <br>
alias gp='git pull' <br>
alias gpo='git push origin' <br>
alias gpom='git push origin main' <br>
alias gpr='git pull --rebase' <br>
alias gr='git rebase' <br>
alias gs='git status' <br>
alias gss='git status --short' <br>
alias gst='git stash' <br>
alias gsta='git stash apply' <br>
alias gstd='git stash drop' <br>
alias gstl='git stash list' <br>
alias gstp='git stash pop' <br>
alias gsts='git stash save' <br>


# -------
# Aliases
# -------
alias clr="clear"  Clear your terminal screen <br>
alias cd.="cd .. Go back <br>
alias ll="ls -al"  List all files in current directory in long list <br>
alias lsa="ls -a"  List all file and Hidden file in current Directory <br>
alias o="open ."  Open the current directory in Finder <br>
alias ut="uptime"  Computer uptime <br>
