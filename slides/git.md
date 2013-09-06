<style>
  .reveal h1 {
    font-size: 130px;
  }
</style>
# Introduction to VCS

## ThoughtWorks Pune

---

# How do you manage your your assignments or projects?

----

* Create different directories named project1, project2..
* Work in groups and then copy paste files into the project directory

----

### Y U no use my code?

<img src="/images/yuno.png" alt="Git structure" width=500 height=500/>

---

# VCS =
# Version Control System

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

![git filesystem](/images/git-filesystem.png "Git structure")

----

### The three states

* committed, modified and staged.

![git three states](/images/git-file-states.png "Git File states")

---

# Getting Started

----

### Install Git

* Ubuntu, Debian, Mint

$ sudo apt-get install -y git-core

* Fedora, Red Hat, CentOS

$ sudo yum install -y git-core

* Windows

http://msysgit.github.io/

----

### Introduce yourself to git

$ git config --list

$ git config --global user.name = "Amazing bros"

$ git config --global user.email = "foobar@amazing-bros.com"

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

# Lets change something in your new git repository

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

![git log](/images/git-log.png "git log")

---

# Github