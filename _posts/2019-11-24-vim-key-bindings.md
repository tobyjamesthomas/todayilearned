---
layout: post
title: "Why vim uses hjkl as arrow keys. ⬅️⬇️⬆️➡️"
description: ""
thumb_image: "posts/vim-key-bindings/ADM-3A.svg"
tags: [dev, vim]
---

TIL, many of vim's key bindings, such as the use of `hjkl` for arrow keys, originate from the Lear Siegler <a href='https://en.wikipedia.org/wiki/ADM-3A' target='_blank'>ADM-3A</a> terminal, which Bill Joy used to create the vi editor. Looking at the ADM-3A's keyboard layout, we can notice other distinctive features:
- The placement of `Esc` and `Ctrl` are much more convenient
- The colon key `:`, used in Command mode, can be used without holding `Shift`
- Home and `~` share the same key, which is why `~` represents the home directory in Unix-like operating systems

{% include image.html path="posts/vim-key-bindings/ADM-3A.svg" path-detail="posts/vim-key-bindings/ADM-3A.svg" caption="ADM-3A keyboard layout (<a href='https://en.wikipedia.org/wiki/ADM-3A#/media/File:KB_Terminal_ADM3A.svg' target='_blank'>source</a>)" alt="ADM-3A keyboard layout" %}
