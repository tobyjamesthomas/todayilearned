---
layout: post
title: "Git stash individual files. 🗄"
description: ""
thumb_image: "posts/git-stash-push/git-yancy-min.jpg"
tags: [dev, git]
---

TIL, you can stash individual files in a working directory with `git stash push`, followed by the paths of the files you want to stash.

For example, `git stash push supe.rb pup.py` will only stash `supe.rb` and `pup.py`, which can then be retrieved using `git stash pop` or `git stash apply`.

In practice, when working on a feature, I can use `git stash push app/ui` to stash frontend changes, to separate frontend and backend commits.

Learn more about <a href='https://git-scm.com/docs/git-stash' target='_blank'>git stash</a>.
