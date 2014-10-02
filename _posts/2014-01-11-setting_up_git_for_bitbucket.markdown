---
layout: post
title: "Setting up bitbucket for git"
date: 01 Oct 2014
categories: git programming bitbucket
---

Following are the outline steps to setup bitbucket four your source code version control using
git. The following steps requires that you have already setup git on your machine.

1. Setup an account at [https://bitbucket.org](https://bitbucket.org)
2. Generate a keypair using ssh-keygen. It's better to enter a passphrase.
3. Take the .pub key generated in step 2 and upload it to bitbucket.   
4. Add the private key created in step 2 to ssh-agent via ssh-add 
5. Add the user name and gmail to git as follows

>    prompt> git config --global user.name = joeshchmo

>    prompt> git config --global user.email = joeshchmo

>    prompt> git config -l 

6. Add the remote url(s) to git. You can replace `origin` in the below command for any number 
of other remote urls.   

>    prompt> git remote add origin git@bitbucket.org:joeshcmo/joeschmo.git   

>    prompt> git remote add githubbkp git@bitbucket.org:joeschmo/joeschmo.git 

