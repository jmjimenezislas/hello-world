# hello-world
<h3>My first repository on GitHub.</h3>

This repository has been created in order to test how GitHub works. No "great expectations" shoud be expected!!!

I like :coffee:, :books: and :computer:.

Molina de Segura (Murcia, Spain).

<hr/>

These paragraphs (and the html tags) have been written in gedit, a text editor for GNU/Linux Gnome desktop.

Done in my computer, I intend to test the following:

1. Update the repository local copy in my computer, always working from the directory where it is installed:<br/>
<code>jmjimenezislas@debian-netbook:~/Documents/informática/GitHub/Git/hello-world$ git pull https://github.com/jmjimenezislas/hello-world/</code><br/>
<sup>*</sup>where <em>jmjimenezislas/hello-world</em> stands for <em>name_of_repository</em>.
2. Once updated my local copy, I make some changes, what it is being read now, and see the pending changes with the following command:<br/>
<code>$ git status</code>
3. Now that the changes have been presented and I have been told that README.md file has been modified, through the line command I add the changes to the "repo" (= repository):<br/>
<code>$ git add .</code><br/>
<sup>*</sup>Yes, the "full stop" (.) belongs to the command.<br/>
I tag those changes. It is useful to know what is has been done to explain the nature of the modifications:<br/>
<code>$ git commit -m "README.md changed" -a</code>
4. Up to now Git has been told we have (some) changes, but only locally applied; I add them to the GitHub repository (to make them available to everyone 'cause the repo is <em>public</em>) with:<br/>
<code>$ git push https://github.com/jmjimenezislas/hello-world/</code>
5. GitHub will upload the changes once logged with my user name and password (if I have writing rights).

Now these changes are available for all of us!

The changes made in README.md file have been made thanks to the following source:<br/>
<a href="https://victorhckinthefreeworld.wordpress.com/2012/09/26/git-y-github-tutorial-basicode-uso-bajo-gnulinux/">Git and GitHub GNU/Linux basic guide</a> [author: <a href="https://victorhckinthefreeworld.wordpress.com/author/victorhck/">victorhck</a>]<br/>
I have merely followed and translated it.

<hr/>

Some <em>html</em> changes have been made to improve appearance.

<hr/>

Command line history:

<code>jmjimenezislas@debian-netbook:~/Documents/informática/GitHub/Git/hello-world$ cat README.md<br/>
<span class="toRed" color="red"># hello-world
My first repository on GitHub.

This repository has been created in order to test how GitHub works. No "great expectations" shoud be expected!!!

I like :coffee:, :books: and :computer:.

Molina de Segura (Murcia, Spain).</span>
$ git pull https://github.com/jmjimenezislas/hello-world/
From https://github.com/jmjimenezislas/hello-world
 * branch            HEAD       -> FETCH_HEAD
Already up-to-date.
$ ls
hello-world
$ cd hello-world
$ ls -la
total 36
drwxr-xr-x 3 jmjimenezislas jmjimenezislas  4096 gen 18 12:28 .
drwxr-xr-x 3 jmjimenezislas jmjimenezislas  4096 gen 18 12:29 ..
drwxr-xr-x 8 jmjimenezislas jmjimenezislas  4096 gen 18 12:30 .git
-rw-r--r-- 1 jmjimenezislas jmjimenezislas 18027 gen 18 11:32 LICENSE
-rw-r--r-- 1 jmjimenezislas jmjimenezislas  2151 gen 18 12:28 README.md
$ git status
# On branch master
# Changes not staged for commit:
#   (use "git add <file>..." to update what will be committed)
#   (use "git checkout -- <file>..." to discard changes in working directory)
#
#	modified:   README.md
#
no changes added to commit (use "git add" and/or "git commit -a")
$ git commit -m "README.md changed" -a
[master d4b4f72] README.md changed
 1 file changed, 27 insertions(+), 1 deletion(-)
$ git status
# On branch master
# Your branch is ahead of 'origin/master' by 1 commit.
#
nothing to commit (working directory clean)
$ git push https://github.com/jmjimenezislas/hello-world/
Username for 'https://github.com': jmjimenezislas
Password for 'https://jmjimenezislas@github.com': 
Counting objects: 5, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.29 KiB, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/jmjimenezislas/hello-world/
   10ce8b9..d4b4f72  master -> master
$ git status
# On branch master
# Your branch is ahead of 'origin/master' by 1 commit.
#
# Changes not staged for commit:
#   (use "git add <file>..." to update what will be committed)
#   (use "git checkout -- <file>..." to discard changes in working directory)
#
#	modified:   README.md
#
no changes added to commit (use "git add" and/or "git commit -a")
$ git commit -m "README.md changed for improving preview" -a
[master deb2a74] README.md changed for improving preview
 1 file changed, 9 insertions(+), 9 deletions(-)
jmjimenezislas@debian-netbook:~/Documents/informática/GitHub/Git/jmjimenezislas/hello-
world$ git push https://github.com/jmjimenezislas/hello-world/
Username for 'https://github.com': jmjimenezislas  
Password for 'https://jmjimenezislas@github.com': 
Counting objects: 5, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 380 bytes, done.
Total 3 (delta 1), reused 0 (delta 0)
To https://github.com/jmjimenezislas/hello-world/
   d4b4f72..deb2a74  master -> master
</code>
