---
layout: post
title: "Setting up bitbucket for git"
date: 2014-10-01
categories: programming git
---
Following are the outline steps to setup bitbucket four your source code version control using
git. The following steps requires that you have already setup git on your machine.  
* Setup an account at [https://bitbucket.org](https://bitbucket.org)
* Generate a keypair using ssh-keygen. It's better to enter a passphrase.
* Take the .pub key generated in step 2 and upload it to bitbucket.   
* Add the private key created in step 2 to ssh-agent via ssh-add 
* Add the user name and gmail to git as follows
~~~
prompt> git config --global user.name = joeshchmo
prompt> git config --global user.email = joeshchmo
prompt> git config -l 
~~~
6. Add the remote url(s) to git. You can replace `origin` in the below command for any number 
of other remote urls.   
~~~
prompt> git remote add origin git@bitbucket.org:joeshcmo/joeschmo.git   
prompt> git remote add githubbkp git@bitbucket.org:joeschmo/joeschmo.git 
~~~

