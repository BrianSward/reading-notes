# Day 2 - 6/28/2022

## Notes on [Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

- meta comment, hah solid understanding of terminal is a prereq, i'm screwed

## What is Git?

- Git is a DVCS that stores data in a file system made up of snapshots
- Git mostly relies on local operations
- Tracks changes
- Minimize loss of data
- Tracks state

## History of Git

- Started in '05... dear god [here](https://en.wikipedia.org/wiki/GitHub)

## Customization

- GUI is available - [GUI](https://git-scm.com/downloads/guis)
- Can also adjust user settings, colors, and such

## Git Repository

- Can be made, imported, cloned
- Made of three components Working Directory (where files live), Index (staging area), Head (points to most recent commit)
- Saves are either Tracked or Untracked, not sure what this means
- [ ] All this commiting changes and file status sh1t makes no sense, find a youtube video about this
  - The Life Cycle of File Status, Check File Status, Tracking and Staging a New File, Committing a File, Committing All Changes, Pushing Changes, Stashing Changes

## Remote Repositories - Versions which live online

- _Cloned Reponsitories_ - they can be remote as well as local
- _Seeing Your Remotes_ - By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.
- _Adding Remotes_ - Can add them also
- _Fetching_ - or get them
- _Pushing_ - allows for changing
- _Renaming/Removing Remotes_ - self explainitory

## Undoing Actions

- You can undo actions
- Various ways, Commit Mistakes, Unstaging a File, Undo a Committed Snapshot, Unmodifying a File

## Branching

- Common trait of version control systems
- you create branches of a central repository, collaborators are able to work simultaneously via multiple branches, without affecting this main repository.
- [ ] Watch a you tube video on this! This seems very important when you actually work with other people
- Can also switch a branch, list branches, and other things

## Merging

- This is bring multiple branches together
- _Fast-Forward Merging_ current branch’s pointer moves forward to the most recent commit for the branch being merged in
- _No Fast-forward_ the git merge --no-ff \<branch> command, will have new commit object is created. often used to prevent the loss of historical information regarding a merged-in branch.
- _Three-way Merge_ In cases of branches diverging, fast-forward merges are not an option. A three-way merge can be used when fast-forward merges are not an option due to branch diverging.
- _Fetch and Merge_ To easily fetch and merge remote changes, use the git pull command in your working directory.
- _Deleting Branches_ After you’ve merged branches, and they’re no longer needed, you can easily delete them with the -d flag.
- _Merge Conflicts_ usually when Git will not be able to complete the merge cleanly. conflicts must be dealt with manually. Portions of files with unresolved merge conflicts will be labeled “unmerged”. You can easily locate areas of merge conflict via Git’s conflict resolution markers, which appear in applicable files.
- _Preview Changes_ To preview changes for merging, use the git diff command in the following format
- _Listing Branches_ To list local branches, use the git branch command. The branch currently being worked on will have an asterisk next to its name.
- You can see the _See Latest Commits_ use the git branch-v command

## Rebasing

- A popular alternative to merging.

### The Basics

- starts with the common ancestor of two branches - where you are and where you’re rebasing onto. Then, the diffs resulting from each commit of your current branch are saved to temporary files, and the current branch gets reset to the same commit as that of the branch you are rebasing onto. Last but not least, all changes get applied to the branch you are rebasing onto.
[ ] ehh go find a youtube video
- Rebase vs. Merge
  - Pro-merge argument - The true commit history of a repository should not be altered because it’s a record of occurrences.
  - Pro-rebase argument - Commit histories should be polished and well edited.

## Log

- You can utilize the git log command to view committed snapshots. You can use the command to see a project’s history, use a filter, and find specific modifications. Here are example uses of the git log command:

## Tagging

- With the use of tags, Git can flag certain points in a project’s history as being significant.
- _Create a Tag_ - Can be lightweight and annotated.
  - Lightweight - A lightweight tag is a pointer to a particular commit – like a branch.
  - Annotated - An annotated tag is stored in the Git database as a full object, containing a tagging message, tagger name and email, and tag date. Annotated Tags can also undergo signing and verification with GNU Privacy Guard (GPG). The best practice is to use annotated tags when possible, to allow for storage of valuable information and privacy safeguards.
- _Create Annotated Tags_ - To create an annotated tag, use -a with the git tag command
- _Create Lightweight Tags_ - A lightweight tag for commits only holds a checksum. To create a lightweight tag, simply utilize the git tag command without using -a, -s, or -m.
- _Tag Sharing_ Users must push tags to shared servers after creation because, by default, the git push command does not send tags to remote servers.
- _Tag Checkout_ Because you cannot move tags around, they cannot be checked out in Git. However, you can create a new branch at a specific tag with the git checkout -b [branchname][tagname] command.

## Aliases

- Aliases allow users to navigate Git in an easier fashion. you can make aliases for Git commands, thus you don't need to type out an entire default Git command. You can set up aliases using the git config command.

## Ignoring Files

- Use .gitignore, for untracked files consist of uncommitted files recently added to a project or compiled binaries with extensions such as .exe and .obj. Git allows users to avoid this situation by ignoring certain files by sending them to a special file with the name

## Distributed Workflows

- _Distributed workflows_ => allow collaboration. Every developer using Git can be both a node and a hub; this means he/she can own a main repository which collaborators contribute to and base their work off of while also contributing code to other repositories. This opens up the possibilities for workflows immensely.

For now, we are only going to discuss a couple of the most common distributed workflows.

- _Centralized Workflow_ - Centralized workflow has one main hub accepting code

- _Integration-Manager Workflow_ involves multiple remote repositories (This workflow is commonly found with hub-centered resources)

## GitHub

As previously mentioned, GitHub is a hub-focused tool which facilitates Integration-Manager Workflow. It is the largest existing host for Git repositories and is used by millions of developers worldwide. A high percentage of Git repositories reside on GitHub, and this resource is used by many open source projects.

- _Getting Started_ you must set up a free user account at [Git Hub](https://github.com).

- _Contributing to Projects_ - when you do not have push privileges for, you can “fork” a project,

- _General Workflow_ revolves around Pull Requests.

Here are the main steps of the GitHub collaboration workflow:

- Create a topic branch from master.
- Commit changes for the project.
- Push the topic branch to the GitHub project.
- Open a Pull Request.
- Confer with team and perform additional commits, if applicable.
- The project owner closes or merges the Pull Request.
