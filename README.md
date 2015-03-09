# git_study

# Tutorials
http://git-scm.com/book/en/v2
http://git-scm.com/book/zh/v1

# Install for Mac
1. install <a href="http://brew.sh">homebrew</a>
2. $ brew install git
3. to cover the old version installed by xcode, echo "export PATH=/usr/local/bin:/usr/local/sbin:$PATH" >~/.bashrc
4. use "git --version" and "which git" to confirm

# Tips
* Auto-Completion
Copy <a href="https://github.com/pomn/git/blob/master/contrib/completion/git-completion.bash">git-completion.bash</a>  to your home directory, and add this to your .bash_profile file: "source ~/git-completion.bash"

* Alias
Edit ~/.gitconfig
[alias]
    st = status -s
    ci = commit
    l = log --oneline --decorate -13
    ll = log --oneline --decorate
    co = checkout
    br = branch
    rb = rebase
    unstage = reset HEAD --
    last = log -1 HEAD
    logg = log --pretty=oneline --graph