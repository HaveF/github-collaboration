github-collaboration
====================

Training course for GitHub.

This course is used for training newbies the basic concept and
workflows about Github.

**Table of Contents**

* [Background](#background)
* [SWC's repo maze :dizzy_face:](#swcs-repo-maze-dizzy_face)
* [Web based workflow (The easiest)](#web-based-workflow-easiest)
* [Command line or gui tools based workflow (The most flexible)](#command-line-or-gui-tools-based-workflow-the-most-flexible)
* [Tips](#tips)


Background
----------

You should know some basic concepts (or commands) of Git. Like:

* branch
* checkout
* clone
* remote
* push
* pull
* repository (a.k.a. "repo")

If you want to collaborate to others well, you also should know:

* rebase
* commit --amend
* cherry-pick

SWC's repo maze :dizzy_face:
----------------------------

![many repos](https://github.com/swcarpentry/bc/raw/gh-pages/img/readme/step3.png)

It is a little bit crowded:family::two_women_holding_hands::dolls::couple::two_men_holding_hands: 
when you see it in first time.

Let's forget it first.

- [TODO]add the basic figure of repo and cloned repo
- [TODO]explain the repo `YYYY-MM-DD-site`

Web based workflow (The easiest)
--------------------------------

Demo and practice time!

Reference: [GitHub Flow in the Browser](https://github.com/blog/1557-github-flow-in-the-browser)

1. fork
2. make a **new branch**
3. change
4. send PR (pull request)
5. discuss with others
6. improve it
7. accepted

Prrrrrrrrractice items:
- [ ] Fix the `Prrrrrrrrractice` to `Practice`
- [ ] Fix the title `github-collaboration` to `GitHub-collaboration`
- [ ] Fix whatever you want
- [ ] Send A PR
- [ ] Discuss it. Include:
    - [ ] Make a reference to other issue
    - [ ] Reply discussion in mail
    - [ ] Use @ to mention other

Prons and cons:
* Easy and quick to use
* Friendly to users (also include newbies)
* Even no need to install Git!
* Less disruptive workflows
* (x)Hard to reuse (like pull new commits from the original repo, rebase the PR)

Command line or gui based workflow (The most flexible)
------------------------------------------------------

Demo time! (No practice because the limited time:sweat_smile:)

Compare with [Web based workflow (The easiest)](#web-based-workflow-easiest).

1. fork --> fork on the web, then clone to local
2. make a **new branch**  --> checkout a new branch at local
3. change --> may include checkout a new branch for PR, rebase, cherry-pick, etc.
4. send PR (pull request)  --> push the new local branch to your forked repo, then send PR on the web
5. discuss with others
6. improve it
7. accepted


Tips
----

* Be nice:bowtie:, be polite, remember, you are discussing with people:bow: who have different personality only by text:memo:,
maybe you can use [EMOJI](http://www.emoji-cheat-sheet.com/) when you are discussing:wink:, and reply to contributors
as soon as possible:+1:, especially you are the repo's owner:innocent:.
* Write the commit message more informative (On the other hand, you need to hide the commit detail)
