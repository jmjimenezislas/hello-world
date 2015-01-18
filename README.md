# hello-world
<h3>My first repository on GitHub.</h3>

This repository has been created in order to test how GitHub works. No "great expectations" shoud be expected!!!

I like :coffee:, :books: and :computer:.

Molina de Segura (Murcia, Spain).

<hr/>

These paragraphs (and the html tags) have been written in gedit, a text editor for GNU/Linux Gnome desktop.

Done in my computer, I intend to test the following:

1. Update the repository local copy in my computer, always working from the directory where it is installed:
<code>jmjimenezislas@debian-netbook:~/Documents/informática/GitHub/Git/hello-world$ git pull https://github.com/jmjimenezislas/hello-world/</code>
<sup>*</sup>where <em>jmjimenezislas/hello-world</em> stands for <em>name_of_repository</em>.
2. Once updated my local copy, I make some changes, what it is being read now, and see the pending changes with the following command:
<code>$ git status</code>
3. Now that the changes have been presented and I have been told that README.md file has been modified, through the line command I add the changes to the "repo" (= repository):
<code>$ git add .</code>
<sup>*</sup>Yes, the "full stop" (.) belongs to the command.
I tag those changes. It is useful to know what is has been done to explain the nature of the modifications:
<code>$ git commit -m "README.md changed" -a</code>
4. Up to now Git has been told we have (some) changes, but only locally applied; I add them to the GitHub repository (to make them available to everyone 'cause the repo is <em>public</em>) with:
<code>$ git push https://github.com/jmjimenezislas/hello-world/</code>
5. GitHub will upload the changes once logged with my user name and password (if I have writing rights).

Now these changes are available for all of us!

The changes made in README.md file have been made thanks to the following source:
<a href="https://victorhckinthefreeworld.wordpress.com/2012/09/26/git-y-github-tutorial-basicode-uso-bajo-gnulinux/">Git and GitHub GNU/Linux basic guide</a> [author: <a href="https://victorhckinthefreeworld.wordpress.com/author/victorhck/">victorhck</a>]
I have merely followed and translated it.
