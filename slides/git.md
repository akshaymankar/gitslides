<style>
  .reveal h1 {
    font-size: 130px;
  }
  .reveal h1, .reveal h2, .reveal h3, .reveal h4, .reveal h5, .reveal h6 {
    text-transform: inherit;
   }
</style>
# Introduction to VCS

## ThoughtWorks Pune

---

## How do you
## manage
## your assignments 
## or projects?

----

* Create different directories named project1, project2..
* Work in groups and then copy paste files into the project directory

----

### Y U no write code that works !

<img src="/images/yuno.png" alt="Git structure" width=500 height=500/>

---

# VCS
## Version
## Control
## System

----

# Why?

----

### We are programmers!

* We write something and then we change our minds.
* We want to know why was something done the way it was.
* We want to collaborate.

----

# VCS GIVES

* Reversibility
* Annotation
* Concurrency

---

![git kid](/images/git-kid.jpg "What is Git?")

----

<img src="/images/git-filesystem.png" style="width: 800px" />

----

### The three states

* committed, modified and staged.

![git three states](/images/git-file-states.png "Git File states")

---

# Getting Started

----

### Install Git

* Ubuntu, Debian, Mint

$ sudo apt-get install git-core

* Fedora, Red Hat, CentOS

$ sudo yum install git-core

* Windows

http://msysgit.github.io/

----

### Introduce yourself to git

$ git config --global user.name = "Amazing bros"

$ git config --global user.email = "foobar@amazing-bros.com"

$ git config --list

----

### Create your first repository

$ mkdir my_ultimate_vcs

$ cd my_ultimate_vcs

$ git init

![git init](/images/git-init.png "Initialize your git repository")

----

### Create your first file

$ touch README

$ git status

![git status1](/images/git-status1.png "git status")

----

### Stage your file

$ git add README

$ git status

![git add](/images/git-add.png "git add")

----

### First commit

$ git commit -m "First commit"

$ git status

![git commit](/images/git-commit.png "git commit")

----

### File status lifecycle

![file status lifecycle](/images/file-status-lifecycle.png "File status lifecycle")

---

# Lets change something

----

### Change your README

$ echo "My first project" >> README

$ git status

![git status2](/images/git-status2.png "git status")

----

### Find out what you changed

$ git diff

![git diff](/images/git-diff.png "git diff")

----

### Commit your changes

$ git commit -am "Update README"

![git commit2](/images/git-commit2.png "git commit2")

----

### See your history

$ git log

![git log](/images/git-log.png "git log")

----

### See what you changed

$ git show

![git show](/images/git-show.png "git show")

---

# Github

![octocat](/images/octocat.png "octocat")

----

## Hosted git
## Hub for open source projects

----

# Remotes

![Remotes](/images/remotes.jpg "Remotes")

----

$ git remote add origin &lt;URL here&gt;

----

$ git push --set-upstream origin master

----

## Clone other's code !

$ git clone &lt;some url&gt;

---

# Resources

----

* Pro Git: http://git-scm.com/book
* Try Git: http://try.github.io/
* Git Immersion: http://gitimmersion.com/
* $ man git
* $ git &lt;command&gt; --help

---

# Thanks
<img src="/images/ironcat.jpg" alt="Git structure" width=500 height=500/>
