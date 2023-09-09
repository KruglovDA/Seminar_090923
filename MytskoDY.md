# Git Commands
## SETUP
* <u> git config --global user.name “[firstname lastname]”</u> - *__set a name__ that is identifiable for credit when review version history*
* <u> git config --global user.email “[valid-email]”</u> - *__set an email__ address that will be associated with each history marker*
* <u>git config --global color.ui auto</u> - *__set automatic command line coloring__ for Git for easy reviewing*
## SETUP & INIT
1. <u>git init</u> - *__initialize__ an existing directory as a Git repository*
2. <u>git clone [url]</u> - *__retrieve an entire__ repository from a hosted location via __URL__*
## STAGE & SNAPSHOT
* <u>git remote add [alias] [url]</u> - *__add a git URL__ as an alias*
* git fetch [alias] - *__fetch down all the branches__ from that Git remote*
* git merge [alias]/[branch] - *__merge a remote branch into your current branch__ to bring it up to date*
* git push [alias] [branch] - *__Transmit local branch commits to the remote repository branch__*
* git pull - *__fetch and merge any commits from the tracking remote branch__*
## BRANCH & MERGE
* git branch - _**list your branches**. a * will appear next to the currently active branch_
* git branch [branch-name] - _**create a new branch** at the current commit_
* git checkout - *__switch to another branch__ and check it out into your working directory*
* git merge [branch] - *_merge the specified branch’s history into the current one__*
* git log - _**show all commits** in the current branch’s history_
## INSPECT & COMPARE
* git log - *show the commit history for the currently active branch*
* git log branchB..branchA - *show the commits on branchA that are not on branchB*
* git log --follow [file] - *show the commits that changed file, even across renames*
* git diff branchB...branchA - *show the diff of what is in branchA that is not in branchB*
* git show [SHA] - *show any object in Git in human-readable format*
## TRACKING PATH CHANGES
 * git rm [file] - *delete the file from project and stage the removal for commit*
* git mv [existing-path] [new-path] - *change an existing file path and stage the move*
* git log --stat -M - *show all commit logs with indication of any paths that moved* 
## IGNORING PATTERNS
1. __logs/__
2. __*.notes__
3. __pattern*/__

**Save a file with desired paterns as .gitignore with either direct string matches or wildcard globs.**
* git config --global core.excludesfile [file] - *system wide ignore patern for all local repositories*
## SHARE & UPDATE
__Retrieving updates from another repository and updating local repos__
* git remote add [alias] [url] -  __add a git URL as an alias__
* git fetch [alias] - __fetch down all the branches from that Git remote__
* git merge [alias]/[branch] - __merge a remote branch into your current branch to bring it up to date__
* git push [alias] [branch] - __Transmit local branch commits to the remote repository branch__
* git pull - __fetch and merge any commits from the tracking remote branch__
## REWRITE HISTORY
__Rewriting branches, updating commits and clearing history__
* git rebase [branch] - __apply any commits of current branch ahead of specified one__
* git reset --hard [commit] - __clear staging area, rewrite working tree from specified commit__
## TEMPORARY COMMITS
*Temporarily store modified, tracked files in order to change branches*
* git stash - __Save modified and staged changes git stash list list stack-order of stashed file changes__
* git stash pop - __write working from top of stash stack git stash drop discard the changes from top of stash stack__
***
## TEMPORARY COMMITS
*Temporarily store modified, tracked files in order to change branches*
* git stash - __Save modified and staged changes git stash list list stack-order of stashed file changes__
* git stash pop - __write working from top of stash stack git stash drop discard the changes from top of stash stack__
***
# Syntax of Markdown file
## Selection if text
<u> words </u> - underline words\
* words - create unnumbered list
- words - create unnumbered list
+ words - create unnumbered list
1. words - create ordered list
----
__words__ or **words** - in bold\
*words* or _words_ - in italic\
~~words~~ - crossed out\
*** ___ --- - horizontal line\
## blockquotes
> # words - blockquotes\
>> blockquotes second level\
>
>continue main blockquotes 
>>> blockquotes third level
>
---

## Checkbox
  - [x] Yes
  - [ ] No

## LINKS
LINKS syntax MK [tap to see syntax Markdown](https://paulradzkov.com/2014/markdown_cheatsheet/).\
LINKS syntax MK [first][1], [second][2].

[1]: https://skillbox.ru/media/code/yazyk-razmetki-markdown-shpargalka-po-sintaksisu-s-primerami/#stk-1 "first"
[2]: https://texterra.ru/blog/ischerpyvayushchaya-shpargalka-po-sintaksisu-razmetki-markdown-na-zametku-avtoram-veb-razrabotchikam.html (second) 

---
## Input code
it's command for it - [``````]
```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```
## Code in sentences 
`span class="caret"></span>` command ``
## Картинки
### Add pictures first way
Picture of aniamls

![Here you can see different animals](animals.jpg)

#### ADD second way to past Picture
Tap on the picture of animals and see more images or go down and see special links to know more about animals or click here and read 
[books about animals](https://www.google.com/search?q=books+about+animals&oq=books+about+animals&aqs=chrome..69i57j0i10i67i650j0i512l8.4314j0j7&sourceid=chrome&ie=UTF-8).

[![Pictures of animals](All_animals.jpg)](https://www.google.com/search?q=sunset&tbm=isch&ved=2ahUKEwisvb2isJGBAxUVzQIHHXZxAdMQ2-cCegQIABAA&oq=sunset&gs_lcp=CgNpbWcQAzIFCAAQgAQyBwgAEIoFEEMyBwgAEIoFEEMyBwgAEIoFEEMyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQ6BAgjECdQ4BBY9BhgwhtoAHAAeACAAYABiAGPBpIBAzEuNpgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=8wX2ZOz3IJWai-gP9uKFmA0&bih=650&biw=1396#imgrc=jclA5L_XckABuM)

You can tap [link][1] and see fishes or [here][2] to watch videos about animals.

[1]: https://www.google.com/search?q=fishes&tbm=isch&ved=2ahUKEwji-bGvhJOBAxWa7bsIHeOWDigQ2-cCegQIABAA&oq=fishes&gs_lcp=CgNpbWcQAzIFCAAQgAQyBwgAEIoFEEMyBQgAEIAEMgUIABCABDIHCAAQigUQQzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgQIIxAnUKkGWPANYLUQaABwAHgAgAHnAogB_AmSAQcwLjYuMC4xmAEAoAEBqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=WuT2ZOLkOJrb7_UP4626wAI&bih=650&biw=1396 (link) 

[2]: https://www.youtube.com/results?search_query=animals+in+nature (here)

## Work with remote repository