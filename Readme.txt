1. `git init` -> Power your folder to managed by git, and initialises a new empty repository. 
It also creates a .git folder that has all the relevant logic to manage versions of your project.

2. `Working Area` -> There can be a bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not managed by git yet. A file 
which is in working area is considered to be not in the staging area. When we do `git status`
and we see a bunch of `untracked file` then these are called to be in the working area.

3. `staging area` -> What all files are going to part of the next version that we will create.
This staging area is the place where git knows what changes will be done from the last version
to the next version.