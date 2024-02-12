`sudo su`

Create user = `useradd -m altschool`

Add password = `passwd altschool`

Log into user = `su altschool`

Change to home = `cd ~`

`pwd`

Create directories = `mkdir code tests personal misc`

A. `cd /home/altschool/tests`

  `pwd`

B. `cd ~`

   `pwd`
   
  `cd tests`
    
  `pwd`

C. `cd ..`

`ls`

`cd misc`

`pwd`

`echo Hello A > fileA`

`ls`

`cat fileA`

D. `pwd`

`echo > fileB`

`ls`

E. `pwd`

`cp fileA fileC`

F. `cp fileB fileD`

`rm fileB`

Though fileB is empty, implying that fileD is also empty

G.  `pwd`

`cd ..`

`tar -cvf misc.tar misc`

`ls`

H. `ls`

`tar -cz misc.tar.gz misc.tar`

