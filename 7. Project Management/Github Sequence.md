# Introduction
This is the typical sequence to make changes to the Github repository via the Command Line.
It assumes wirking in the `master` branch directly (which is only ok for top level changes only).
For more detailed updates (like Code, Documents, etc.) branching is recommended via `git branch` (cf. .

# Summary
TL;DR: The commands to use are:

    git pull -a
    git add -A
    git pull -a
    git commit -am "This is the commit message"
    git push origin master
    
    
# Nominal Sequence on the Master Branch
## First time
You need to Clone the repository:

    git clone

## Whenever you want to make changes

Pull all latest changes from the Server/Origin/Remote to your Local master repository:

    git pull -a

Check that all is up-to-date:

    git status

Work on the files and create the changes.
Once done, prepare their upload back to the Origin.

See what has changed:

    git status

Add them to the list of changes to be uploaded:

    git add -A

Commit these with a Message to decribe what you did (the following command proceeds by batch, proceed separately for detailed changes):

    git commit -am "This is the commit message describing the changes".

Now they are locked and ready to be pushed back to the Server/Origin/Repository (remember, we worked in a Local copy of the `master`branch directly in this case):

    git push -a

Check that all is up-to-date:

    git status
    
    
    
