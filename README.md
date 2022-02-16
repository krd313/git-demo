#Demo Git Repository

This is the first file in this repo.

##Ipsum junk

xxxx@yyyy:~/Projects/website$ git init
Initialized empty Git repository in /home/xxxx/Projects/website/.git/
xxxx@yyyy:~/Projects/website$ ls -a
.  ..  apple-touch-icon.png  browserconfig.xml  css  favicon.ico  fonts  .git  img  index.html  js  tile.png  tile-wide.png
xxxx@yyyy:~/Projects/website$ 

source /usr/lib/git-core/git-sh-prompt
export PS1="${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u:\[\033[01;34m\]\w\[\033[00m\]\$(__git_ps1)\[\033[00m\] $ "
