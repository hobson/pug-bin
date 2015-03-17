# pug-bin

## PDX Python User Group (PUG) shell scripts

This is a namespace package (sub-package) of the pug package a collection of utilities by and for the PDX Python User Group.

---

## Introduction

Shell scripts for `pug` (PDX Python User Group) to help with NLP, data mining, machine learning, and dev ops

---

## Installation

### On a Posix System

If your a user and not a developer, and have an up-to-date posix OS with the postgres, xml2, and xlst development packages installed, then just use `pip`.

    pip install pug-bin

### Fedora

If you're on Fedora >= 16 but haven't previously installed packages with python bindings to common low level math and database libraries you'll need to install these binary and development packages below before installing pug-bin with pip (see above).

    sudo yum install -y python-devel libxml2-devel libxslt-devel gcc-gfortran python-scikit-learn postgresql postgresql-server postgresql-libs postgresql-devel

### Bleeding Edge

Even the releases are very unstable, but if you want to have the latest, most broken code

    pip install git+git://github.com/hobsonlane/pug-bin.git@master

### Warning

This software is in alpha testing.  Install and use at your own risk.

---

## Development

I love merging PRs and adding contributors to the __authors__ list:

    git clone https://github.com/hobson/pug-bin.git


