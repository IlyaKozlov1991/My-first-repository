# This is a tutorial of Markdown usage

## Before move on, please acquire with descriptions of commands to be used working with Git
Git - versions control system determined to simplify control and follow-up of different versions of one project being developed. It will be oftenly used while studying and working on projects.

1. **git init** - *creates a repository in User's folder where project is stored*
2. **git add** - *adds a file to git*
3. **git commit** - *commits changes applied in added file*
4. **git status** - *shows status of files: whether a file is chamged, tracked or untracked*
5. **git log** - *shows logs with all applied commits*
6. **git diff** - *shows difference between files, commits or branches*
7. **git checkout** - *switches between different versions of files, commits or branches (it is required to specify a name of object you are willing to switch to)*

For better understanding of Git functionality please refer to [Git Website](https://git-scm.com)

## And now it's time to come back to Markdown.
As it's seen from above the text has different styles and it's also ordered. Here below will be explained how it can be done using Markdown syntax.  

## Headings
Enclose text with a sharp (#) from both ends to have a big heading:
# Example_title

Enclose text with double-sharps (##) from both ends to have a small heading:
## Example_title_2

## Italic front
Enclose text with asterisk (*) from both ends to have it written italic - *example.*

## Bold front
Enclose text with double-asterisk (**) from both ends to have it written bold - **example.**

## Unnubered lists
Use a single asterisk to make unordered list:
* One
* Two
* Three

## Numbered lists
Use numbers to make ordered list:
1. One
2. Two
3. Three

## Images
To insert some image start your command with exclamation mark (!) then put some text in brackets [] whcih will be highlighted in case of error and then type name of a desired file in parenthesises ().
For example:
![Something went wrong, try again!](fun_pic.jpg)

## Blockquotes
To create a blockquote, start a line with greater than > followed by an optional space and then type your quote.
> Only a Sith deals in absolut (c) Obi-Wan Kenobi, Star Wars

Blockquotes can also contain another formatings. Like so:
> *Only a Sith deals in absolut* (c) Obi-Wan Kenobi, Star Wars

The upper blockquote is in Italic.

Or something like this:

> *Luke, I am Your Father!*
![Something went wrong, try again!](fun_pic2.jpg)

## Links
To create a link enclose desired text in brackets [] and then immediatelly insert URL in parentheses ().

For example:
Number One education platform is [GeekBrains](https://gb.ru/)

## E-mails or URLs
Just enclose e-mail adress or URL in angle brackets <>.

For example: if you found this tutorial useful, please send your feedback to <ilyakozlovmk91@gmail.com>

For better understanding of Markdown Syntax please refer to [Markdown Website](https://www.markdownguide.org)

27/07/2022

Clonned repository from GitHub

Here belowe are some short explanations of commands used to download and upload remote repositories:

**git clone (link to remote repository)** - *creates a clone of remote repository on your device*

**git pull** - *downloads remote repository and merges it with one currentlly used on device*

**git push** - *uploads repository from device to remote repository*

## It's obvious that studying of a programming requires a lot of time and practice
So just keep working!

30/07/2022

Still working on pull-push

IMPORTANT NOTE: after clonning of remote repository it is required to change directory (without it git will try to call directory which doessnt exist). Need to call **cd (name of directory from downloaded repository)**
