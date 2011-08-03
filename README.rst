=================
Subversion-prompt
=================

Introduction
============

Subversion prompt is a bash script that provide an easy way to modify
your bash prompt to add information about the subversion state of
the current directory.

Usage
=====

To use it, add something like that to your .bashrc ::

    SVNP_HUGE_REPO_EXCLUDE_PATH="nufw-svn$|/tags$|/branches$"
    . ~/bin/subversion-prompt
    # set a fancy prompt
    PS1='\u@\h:\w$(__svn_stat)\$ '

Configuration
=============

See in documentation included in the script.
