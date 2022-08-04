---
title: I'm switching to Neovim
teaser: From Visual Studio Code, to Codium, to Emacs, now Neovim. I've switched for a simple reason. 
date: Created
---

Created on: {{page.date}}

Really, by this, I mean that I'm starting to test Neovim as a replacement for Visual Studio Code.

One of the things that I've learned, is that if you can just make things _easier_ for people with computers (i.e. obfusicate the technical skill required to dothings) then you will have a successful tool/product. Visual Studio Code obfusicated the process by which people were able to customize their text editor. 

## Why Switch to Neovim?

Well, that's probably a really good question. I started a new job recently and the inital laptop I was given was pretty low powered in the hardware department, and I needed a text editor that required much fewer resources than a vscode or [Obsidian](https://obsidian.md/). So, I started with emacs, specifically, [doom emacs](https://github.com/doomemacs/doomemacs), and I really liked it. The only issue I really wasn't having a great time with was how scaling worked on my Framework laptop paired with my typeface of choice, [IBM Plex Mono](https://github.com/IBM/plex). Another thing that I want to point out is that I mostly write plain text in markdown. Org mode was something I was not interested in and, from what I've seen online, that's about 80-precent of the reason to use Emacs.

So, I made the switch to Neovim. I'm using a "mainstream" config in [NvChad](https://nvchad.github.io/). Neovim gives me the tools of a modern text editor without the bloat (read: electron) and with just enough customization to make it exactly how I want. It also has the benefit of being solely focused on the text out-of-the-box. With the extensions that come with NvChad, I was already 90-or-so percent of the way to my ideal setup AND it assumed the font of my terminal. 

## What's Next? 

There are a few things I need to work out. Mostly, it's just getting up to speed with all the keyboard commands. I realize that the fastest way to navigate vim is with the keyboard, so it's a lot of just training my fingers what to do. After that, one of the major things that I need to figure out is how to push my obsidian updates to obsidian sync. The sync process is something that is not able to be triggered without launching the obsidian app. The solution for this one is to switch to using something like [syncthing](https://syncthing.net/) and store the files on my NAS. 

There are still things that I intend to use [codium](https://github.com/VSCodium/vscodium) with. The primary use case is the multicursor support. It's so slick and easy to use. It makes bulk editing so easy. 

Outside of these items, the main focus is just to write more code & text with neovim so that I can figure out what I **do** and **do not** like and how I can start fixing it. 

---

If you've got some good insight, tips, or tricks on using neovim, drop me a line at heath@stepph.sh or [@hhheath_](https://twitter.com/hhheath_). 
