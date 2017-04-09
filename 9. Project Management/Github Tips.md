# Introduction
This quick post captures two sets of info:
- Quick Acces to Github Foratting Tips,
- A recap of a typical sequence to make changes to the Github repository via the Command Line.

# Github Formatting Tips
Basics (that is almost eveything!) are available [here](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

Boxes for Todo Lists are created as instructed [there](https://github.com/blog/1375-task-lists-in-gfm-issues-pulls-comments)

# Github sequence
The following assumes working in the `master` branch directly (which is only ok for top level changes only).

**Note: This is note the proper Github way to do**
Because it is lightweight, it better to Branch early and often for any isolated change or bunch of changes.

This allows for changes to be *discussed* during the Pull Request process vs. being implemented directly.

As a reminder Branching and the Standard Github Flow are recaped [here](https://guides.github.com/introduction/flow/)


For more detailed updates (like Code, Documents, etc.) branching is recommended via `git branch`.

## Summary
TL;DR: The commands to use are:

    git pull -a
    git add -A
    git pull -a
    git commit -am "This is the commit message"
    git push origin master


## Nominal Sequence on the Master Branch
### First time
Move to the Local directory in which you want to work.
Then, clone the Github repository there:

    git clone [the .git link of the repository you want]

### Whenever you want to make changes
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
