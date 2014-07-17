---
layout: page
title: Set up your Dev Environment
tagline:
in_sidebar?: true
---

*This page provides setup information to get you up and running for Rails, Android, and iOS development.*

## General / for everyone
### CRLF
Windows developers need to ensure their text editor is set to use the ```LF``` line ending, instead of the Windows-default of ```CRLF```. See [this post](http://adaptivepatchwork.com/2012/03/01/mind-the-end-of-your-line/) for background information. This does not apply to Windows developers programming from within a Linux virtual machine.

### Git
Git is a tool that we use to track changes we make to our code (version control) and share it with others. We also use GitHub, a website which makes it even easier to share and discuss our code. You'll need to [create a free account on GitHub](https://github.com/signup/free); paid accounts offer extra features, like private repositories no-one else can see.

Next, follow the [GitHub setup guide](https://help.github.com/articles/set-up-git) to set up git on your computer. *Note: There are different instructions for Linux, Mac, and Windows. Follow the right one, especially if you'll be developing within a Linux virtual machine!*

### Text Editors
There are many great text editors for software development. We recommend [SublimeText](http://www.sublimetext.com/3), [Atom](https://atom.io/), or [Vim](http://www.vim.org/).

## Rails
*For OS-specific information to jump right in to the setup process, please see the [GoRails Setup Guide](https://gorails.com/setup). Mac users should consult [our documentation](https://github.com/YaleSTC/wiki/wiki/Setting-Up-Your-Development-Environment-%28OS-X%29) in case errors are encountered.*

Windows users should seriously consider [setting up Ubuntu Linux in VirtualBox](http://www.wikihow.com/Install-Ubuntu-on-VirtualBox); it will be easier that way.

### MySQL
The database backend we use for Rails is called **MySQL**. The database stores information for web apps which can be used in the future, i.e., it is persistent storage (not a temporary cache).

You may use MySQL 5.x, or the open source fork MariaDB version 5.x. Do not use MariaDB 10.x; the database structure has changed and is no-longer 100% compatible with Oracle's MySQL.

### rbenv
We use [rbenv](https://github.com/sstephenson/rbenv) to install Ruby, as it allows us to define specific versions of Ruby for use within each project (as opposed to one, "global" version of Ruby which every app has to use). You can follow [this guide](https://gorails.com/setup) to set up Rails quickly.

## Android
...[stub]...

## iOS
...[stub]...
