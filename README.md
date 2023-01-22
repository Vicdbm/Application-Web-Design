# My data

**Name**: Víctor Daniel Beltrán Miramontes

**ID**: 2797509

**Degree**: IDS

**Semester**: 6th

---
# Subject's Data

**Subject's name**: Web Application Design

**Professor's name**: Carlos Ignacio Hernández Nolasco

---
# What is markdown used for?

* Readme Files
* Forum and Blog posts
* Static Site Generators

---
# Tagging Options
## Headers
We use the "#" sign for headers. The number of "#" that we use reduces the size of the header, up to 6 "#" signs.
* ## H2
* ### H3
* ###### H6

## Italic
We can use surround the text with "*" or with "_". Example: \*Italic\*
* *Italic*

## Strong
We can use double "*" to apply a strong effect. Example: \*\*Strong\*\*
* **Strong**

## Horizontal Rule
To apply a horizontal rule we must use "---" on a blank line.

## Links
To add a link we surround with brackets [] the word we want to use as a link and put the actual link in parenthesis (). Example: \[Link Text\](google.com)
* [My Repository](https://github.com/Vicdbm/Application-Web-Design)

## Lists
For unordered lists we just use a "*" before each element.
* Element

For ordered lists we use "1." before each element
1. First element
1. Second element

# Git Commands

## Check the status of a local repository.

```
   git status 
```
## Add individual files or globally.
To add an individual file:
```
    git add <fileName>
```
To add all the files:
```
    git add .
```
## Add comments to the commit.
Add a commit with a comment:
```
    git commit -m "Your text"
```
Modify the comment of a commit:
```
    git commit --append -m "Your new text"
```
## Upload your changes to the remote repository.
```
    git push <origin> <branch>
```
## Create, browse, and delete branches.
Create a branch:
```
    git branch <branchName>
```
Browse branches:
```
    git branch
```
Delete a branch:
```
    git branch -D <branchName>
```

## Roll back a repository to a specific commit.
```
    git reset --hard <commit_sha>
```