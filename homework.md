# Linus's Homework

## Question 1

What is 2 + 2?

4

## Question 2

What is the opposite of Black?

White

## Question 3

What is the 2 _ 3 _ 6 _ 1 _ 10 \* 34?

12240

## Question 4

What does HTML stand for?

HyperText Markup Language

HTML (HyperText Markup Language) is a descriptive language that specifies webpage structure.
https://developer.mozilla.org/en-US/docs/Glossary/HTML

## Question 5

What is CSS useful for?

CSS (Cascading Style Sheets) is a declarative language that controls how webpages look in the browser.
https://developer.mozilla.org/en-US/docs/Glossary/CSS

## Question 6

Using CSS, how would I select every `<h1>` tag on the page?

```css
h1 {
}
```

## Question 7

What is JavaScript?

JavaScript is a scripting or programming language that allows you to implement complex features on web pages.
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#a_high-level_definition

## Question 8

What three problem does Git & Github solve?

Version Control, Collaboration, Archiving(Backups) and/or Restoring, (and Performance)

## Question 9

What happens when you `fork` a repository?

You create your own copy of that specific remote repository in your own GitHub account.

A fork is a copy of a repository.
Forking a repository allows you to freely experiment with changes without affecting the original project.
https://docs.github.com/en/get-started/quickstart/fork-a-repo

## Question 10

What happens when you clone a repostory?

When you create a repository on GitHub.com, it exists as a remote repository.
You can clone your repository to create a local copy on your computer and sync between the two locations.
https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

## Question 11

What is a Pull Request?

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests

## Question 12

What is the Git History log?

It shows you a history of the commits to the repository.

After you have created several commits, or if you have cloned a repository with an existing commit history, you’ll probably want to look back to see what has happened. The most basic and powerful tool to do this is the git log command.
By default, with no arguments, git log lists the commits made in that repository in reverse chronological order; that is, the most recent commits show up first. As you can see, this command lists each commit with its SHA-1 checksum, the author’s name and email, the date written, and the commit message.
https://www.git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History

## Question 13

What does it meant to "push" changes to Github?

You send(upload) the changes of your local repository to the remote repository stored on Github.
"Use git push to push commits made on your local branch to a remote repository."
https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository

## Question 14

What is Github?

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
https://docs.github.com/en/get-started/quickstart/hello-world

## Question 15

What does it mean to "Commit your changes"?

Similar to saving a file that's been edited, a commit records changes to one or more files in your branch.
Git assigns each commit a unique ID, called a SHA or hash, that identifies:
-The specific changes
-When the changes were made
-Who created the changes
https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits

Create a new commit containing the current contents of the index and the given log message describing the changes. The new commit is a direct child of HEAD, usually the tip of the current branch, and the branch is updated to point to it
https://git-scm.com/docs/git-commit

## Question 16

What program do we use to write code at CodeYourFuture?

Visual Studio Code
https://code.visualstudio.com/

## Question 17

What do you use "Commit Messages" for?

When you make a commit, you must include a commit message that briefly describes the changes.
(This is to help others understand what changes have been made.)
https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits

## Question 18

Where can I look to find help with Git?

The Git Cheatsheet!

The entire Pro Git book, written by Scott Chacon and Ben Straub and published by Apress
https://git-scm.com/book/en/v2

## GitHub CLI Commands & Git Commands used for this Pull Request

1. gh repo fork https://github.com/CodeYourFuture/GitHomeworkFixErrors --fork-name "git-fix-errors" --clone
2. cd git-fix-errors
3. git status
4. git add .
5. git commit -m "completed homework"
6. git push
7. gh pr create
8. base repository: CodeYourFuture/GitHomeworkFixErrors
9. title: London 9 - Baz Murphy - Git&GitHub - Week 1
10. template: pull_request_template.md
11. body: e to open notepad, write body. save. close notepad.
12. submit
