# An introduction to git!

## What is git?
Git is a convenient way to keep track of files, typically code. In it's most basic form you:
1. Tell it which files to track
2. Make checkpoints as you improve your code

That's it!

## So, what is GitHub?
When using git you are keeping track of all your files, however, they are only stored on your computer. We can use git to *push* your code to a *remote*, GitHub is an example of a *remote*

### Compared to OneDrive
Think of git as being like OneDrive without an internet connection, it still keeps track of your files and knows what has been changed. When you connecting to the internet it then uploads your files to OneDrive, this is the equivalent of GitHub.

## Tutorial syllabus

In this tutorial we will cover the following topics:
**cloning**: Creating your own copy of a repository
**branching**: We may have a main *branch*, this contains code we are happy with. If we want to try something out we can create a branch, this gives us a new copy of the *repo*. If we like our changes we can *merge* them back into the main *branch*. For us our main *branch* could be reserved for code which has been used for a submitted paper.
**adding**: Use `git add {my_file.py}` to tell git to keep track of this file
**commiting**: When you want to checkpoint a file you *commit* it with `git checkout {my_file.py}`
**pushing**: When you've made a few changes, or want to show someone else your code you can push it to a *remote* using `git push`
**merging**: If you have made a *branch* and are happy with it you can *merge* it back into the main *branch*
**history**: You can review the git *history* to see what has been *committed* over time
**reverting**: Sometimes *commits* can introduce problems, these can be found by reviewing the *history* and then *reverted*
**issues**: If you're having problems with somebody else's code, it is good practice to write an *issue*, someone can then try to fix this *issue*


## Tasks

1. Clone this repository - when viewing this readme on [github.com](https://github.com/JoshKImperial/git_intro) there is a 'clone'
2. Create a new file `foo.py`, and write a function which squares its input
   1. Add this file and commit you’re changes
3. Add to the file a new function which sums its inputs
   1. Run `git status`, here you can see your new function has been added
   2. Now use `git commit foo.py -m "Added a function for summing inputs"`
4. Add a third function which subtracts its inputs
   1. Re-run step 3’s indented points
5. Run `git push`
   1. Viewing your repo in Github, clicking on ‘commits’ will let you view the repos history
6. 



## Glossary

* Repo - repository - essentially a folder containing code
* *remote* - An online service which stores your code, typically GitHub
