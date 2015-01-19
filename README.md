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

<pre>
<code>jmjimenezislas@debian-netbook:~/Documents/informática/GitHub/Git/hello-world$ cat README.md<br/>
&#35; hello-world<br/><!-- #: &#35;-->
My first repository on GitHub.<br/>
<br/>
This repository has been created in order to test how GitHub works. No "great expectations" shoud be expected!!!<br/>
<br/>
I like :coffee:, :books: and :computer:.<br/>
<br/>
Molina de Segura (Murcia, Spain).<br/>
$ git pull https://github.com/jmjimenezislas/hello-world/<br/>
From https://github.com/jmjimenezislas/hello-world<br/>
&nbsp;&#42; branch            HEAD       -> FETCH_HEAD<br/><!-- *: &#42; -->
Already up-to-date.<br/>
$ ls<br/>
hello-world<br/>
$ cd hello-world<br/>
$ ls -la<br/>
total 36<br/>
drwxr-xr-x 3 jmjimenezislas jmjimenezislas  4096 gen 18 12:28 .<br/>
drwxr-xr-x 3 jmjimenezislas jmjimenezislas  4096 gen 18 12:29 ..<br/>
drwxr-xr-x 8 jmjimenezislas jmjimenezislas  4096 gen 18 12:30 .git<br/>
-rw-r--r-- 1 jmjimenezislas jmjimenezislas 18027 gen 18 11:32 LICENSE<br/>
-rw-r--r-- 1 jmjimenezislas jmjimenezislas  2151 gen 18 12:28 README.md<br/>
$ git status<br/>
&#35; On branch master<br/>
&#35; Changes not staged for commit:<br/>
&#35;   (use "git add <file>..." to update what will be committed)<br/>
&#35;   (use "git checkout -- <file>..." to discard changes in working directory)<br/>
&#35;<br/>
&#35;	modified:   README.md<br/>
&#35;<br/>
no changes added to commit (use "git add" and/or "git commit -a")<br/>
$ git commit -m "README.md changed" -a<br/>
[master d4b4f72] README.md changed<br/>
 1 file changed, 27 insertions(+), 1 deletion(-)<br/>
$ git status<br/>
&#35; On branch master<br/>
&#35; Your branch is ahead of 'origin/master' by 1 commit.<br/>
&#35;<br/>
nothing to commit (working directory clean)<br/>
$ git push https://github.com/jmjimenezislas/hello-world/<br/>
Username for 'https://github.com': jmjimenezislas<br/>
Password for 'https://jmjimenezislas@github.com':<br/>
Counting objects: 5, done.<br/>
Delta compression using up to 2 threads.<br/>
Compressing objects: 100% (3/3), done.<br/>
Writing objects: 100% (3/3), 1.29 KiB, done.<br/>
Total 3 (delta 0), reused 0 (delta 0)<br/>
To https://github.com/jmjimenezislas/hello-world/<br/>
   10ce8b9..d4b4f72  master -> master<br/>
$ git status<br/>
&#35; On branch master<br/>
&#35; Your branch is ahead of 'origin/master' by 1 commit.<br/>
&#35;<br/>
&#35; Changes not staged for commit:<br/>
&#35;   (use "git add <file>..." to update what will be committed)<br/>
&#35;   (use "git checkout -- <file>..." to discard changes in working directory)<br/>
&#35;<br/>
&#35;	modified:   README.md<br/>
&#35;<br/>
no changes added to commit (use "git add" and/or "git commit -a")<br/>
$ git commit -m "README.md changed for improving preview" -a<br/>
[master deb2a74] README.md changed for improving preview<br/>
 1 file changed, 9 insertions(+), 9 deletions(-)<br/>
jmjimenezislas@debian-netbook:~/Documents/informática/GitHub/Git/jmjimenezislas/hello-
world$ git push https://github.com/jmjimenezislas/hello-world/<br/>
Username for 'https://github.com': jmjimenezislas<br/>
Password for 'https://jmjimenezislas@github.com':<br/> 
Counting objects: 5, done.<br/>
Delta compression using up to 2 threads.<br/>
Compressing objects: 100% (3/3), done.<br/>
Writing objects: 100% (3/3), 380 bytes, done.<br/>
Total 3 (delta 1), reused 0 (delta 0)<br/>
To https://github.com/jmjimenezislas/hello-world/<br/>
   d4b4f72..deb2a74  master -> master<br/>
$ git push https://github.com/jmjimenezislas/hello-world/<br/>
Username for 'https://github.com': jmjimenezislas<br/>
Password for 'https://jmjimenezislas@github.com':<br/> 
Counting objects: 5, done.<br/>
Delta compression using up to 2 threads.<br/>
Compressing objects: 100% (3/3), done.<br/>
Writing objects: 100% (3/3), 380 bytes, done.<br/>
Total 3 (delta 1), reused 0 (delta 0)<br/>
To https://github.com/jmjimenezislas/hello-world/<br/>
   d4b4f72..deb2a74  master -> master<br/>
$ git status<br/>
&#35; On branch master<br/>
&#35; Your branch is ahead of 'origin/master' by 2 commits.<br/>
&#35;<br/>
&#35; Changes not staged for commit:<br/>
&#35;   (use "git add <file>..." to update what will be committed)<br/>
&#35;   (use "git checkout -- <file>..." to discard changes in working directory)<br/>
&#35;<br/>
&#35;	modified:   README.md<br/>
&#35;<br/>
no changes added to commit (use "git add" and/or "git commit -a")<br/>
$ git commit -m "README.md changed for adding command line history" -a<br/>
[master 7c6a3a6] README.md changed for adding command line history<br/>
 1 file changed, 86 insertions(+), 1 deletion(-)<br/>
$ git push https://github.com/jmjimenezislas/hello-world/<br/>
Username for 'https://github.com': jmjimenezislas<br/> 
Password for 'https://jmjimenezislas@github.com':<br/>
Counting objects: 5, done.<br/>
Delta compression using up to 2 threads.<br/>
Compressing objects: 100% (3/3), done.<br/>
Writing objects: 100% (3/3), 2.03 KiB, done.<br/>
Total 3 (delta 0), reused 0 (delta 0)<br/>
To https://github.com/jmjimenezislas/hello-world/<br/>
   deb2a74..7c6a3a6  master -> master<br/>
</code>
</pre>

Obviously <em>command line history</em> has been "a bit bigger than shown". The "git push" function has been called at least once more to show this last comment.

<hr/>

Another amendment: now I preview changes through git-cola and/or giggle.
