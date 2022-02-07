---
title: Git Gud
author: Federico Igne · OxRAM
theme: solarized
css: custom.css
---

# What is Git?

:::::: {.columns}

::: {.column width="40%"}

![XKCD 1597: Git (CC BY-NC 2.5)][git]

:::
::: {.column width="60%" }

- a version control system.

- keeps track of code snapshots in time.

- decentralised and content agnostic.

:::
::::::

## What is Git?

![Originally created by Linus Torvalds][torvalds]

## An overview

![][overview]

# Initialise a repository

!["G2 Mobilizon" by David Revoy (CC-BY)][clone]

## Initialise a repository

- `git init`

- `git clone <url>`

# Inspect a repository

!["F5 CHATONS" by David Revoy (CC-BY)][inspect]

## Inspect a repository

<!-- A missing page -->

# Prepare for a new commit

!["B1 Framadate" by David Revoy (CC-BY)][prepare]

## Prepare for a new commit

<!-- A missing page -->

# Commit changes

!["D3 Support" by David Revoy (CC-BY)][commit]

## Commit changes

<!-- A missing page -->

# Branch out

!["D4 Alternative a Framasoft" by David Revoy (CC-BY)][branch]

## Branch out

<!-- A missing page -->

# Collaborate with others

!["C4 Framalang" by David Revoy (CC-BY)][collaborating]

## Collaborate with others

<!-- A missing page -->

# Final remarks

:::::: {.columns}

::: {.column width="40%"}

![XKCD 1296: Git Commit (CC BY-NC 2.5)][git-commit]

:::
::: {.column width="60%" }

- "fear of committing"

- breaking things

- graphical interfaces

:::
::::::

# Where to go from here?

- [Official documentation]

- man pages (`man git <command>`)

- [GitHub resources]

- [Cheatsheet] (PDF)

- [Oh my Git!?] game

# Questions?

!["Erreur 404 illustration" by David Revoy (CC-BY)][questions]


<!-- References -->

[git]: imgs/xkcd_git.png { width=60% }
[git-commit]: imgs/xkcd_git_commit.png { width=100% }
[torvalds]: imgs/torvalds.jpg { width=50% }
[clone]: imgs/clone.jpg { width=50% }
[overview]: imgs/overview.png { width=70% }
[inspect]: imgs/inspect.jpg { width=50% }
[prepare]: imgs/prepare.jpg { width=50% }
[commit]: imgs/commit.jpg { width=50% }
[branch]: imgs/branch.jpg { width=50% }
[questions]: imgs/questions.jpg { width=50% }
[collaborating]: imgs/collaborating.jpg { width=50% }
[Official documentation]: https://git-scm.com/doc
[GitHub resources]: https://docs.github.com/en
[Cheatsheet]: https://education.github.com/git-cheat-sheet-education.pdf
[Oh my Git!?]: https://ohmygit.org/

<!--

Compiled with

    pandoc -t revealjs --slide-level=2 -s presentation.md -o presentation.html

using

- Pandoc 2.13
- Reveal.js 4.2.0

-->
