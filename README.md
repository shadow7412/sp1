sp1
===

Shadow Prompt (The name is a pun on PS1 - the prompt variable)


Installation
============

    cd ~
    git clone git@github.com:shadow7412/sp1.git
    echo source ~/sp1/activate >> ~/.bashrc
    source ~/.bashrc
    cd -

Features
========

    * Minimal
    * Shows how many seconds the previous command ran for (unless it ran for under a second)
    * Changes to red if the previous command failed, or had a non zero return code.
