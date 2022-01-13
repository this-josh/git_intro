# An introduction to git!

Git is a convenient way to keep track of files, typically code. 

## Simple workflow

1. Create a new file `hello_world.py`
2. Tell git to keep track of your new file by running `git add hello_world.py`.
3. Add some content to your file, e.g. `print('hello world!')`
4. Git knows you’ve changed this file, to tell it this is a checkpoint worth remembering use `git commit hello_world.py` . Any future changes will be compared to the most recent commit.

## Tasks

1. Clone this repository
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
