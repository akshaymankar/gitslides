# Introduction to VCS

## ThoughtWorks Pune

---

# How do you manage your your assignments or projects?

----

* Create different directories named project1, project2..
* Work in groups and then copy paste files into the project directory

----

# Y U no use my code?

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

# GIT

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

https://code.google.com/p/msysgit/downloads/list?q=full+installer+official+git

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

----

### Create your first file

$ touch README

----

### Check the status of your repository

$ git status

----

### Stage your file

$ git add README

$ git status

----

### First commit

$ git commit -m "First commit"

$ git status

----

### File status lifecycle

![file status lifecycle](/images/file-status-lifecycle.png "File status lifecycle")

---

# Lets change something in your new git repository

----

### Change your README

$ echo "My first project" >> README

$ git status

----

### Find out what you changed

$ git diff

----

### Commit your changes

$ git commit -am "Update README"

---

# Github