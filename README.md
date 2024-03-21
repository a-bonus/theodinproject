# theodinproject

This is where I'm keeping track of all of my notes as I go through the entirety of The Odin Project

<h3> Git Cheatsheet </h3>

<p>
This is a reference list of the most commonly used Git commands. 

> Commands related to a remote repository:
`git clone git@github.com:USER-NAME/REPOSITORY-NAME.git`
`git push` or `git push origin main` (Both accomplish the same goal in this context)

> Commands related to the workflow:
`git add .` 
`git commit -m "A message describing what you have done to make this snapshot different"`

> Commands related to checking status or log history
`git status`
`git log`

> The basic Git syntax is program | action | destination.

> For example,
> git add . is read as git | add | ., where the period represents everything in the current directory;
> git commit -m "message" is read as git | commit -m | "message"; and
> git status is read as git | status | (no destination).

> Git best practices
Two helpful best practices to consider are:
1. atomic commits
2. leveraging those atomic commits to make your commit messages more useful to future collaborators.

> Atomic commit is a commit that includes changes related to only one feature or task of your program. 
<h4> There are two main reasons for doing this <h4>
1. If something you change turns out to cause some problems, it is easy to revert the specific change without losing other changes

2. It enables you to write better commit messages. 

</p>