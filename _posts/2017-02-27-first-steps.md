---
title: 	"First steps"
categories:
  - DSP2017
tags:
  - DSP2017
  - storytelling
  - dev
---

Hello, World!

This is my first encounter with new technologies for a long time, so I'm a bit nervous ;) Srsly - for last few years I was totally stuck in some horrible projects, with horrible clients, etc. I started burning out and didn't even have energy to try and change my situation. Luckily for me the last project went horribly wrong and I ended to be the person to put the blame onto and get rid off to please the client. The problem solved itself. Lots of my energy drained and my self-confidence shaken in the process, though.

Now I'm free and with a lot of help from my wife ([thanks, Honey!](https://ka1130.github.io/)), who also got fed up with her old profession (graphic designer) and became a front-end developer, I'm starting this small project. Rust Server Manager.

Rust is a survival multiplayer game. It's a sandbox - you wake up on the shore of an island, totally naked, and you have to survive. Initially equipped with only a rock and a torch you have to make shelter, craft some tools and don't get killed. Check it out here: [http://playrust.com/](http://playrust.com/).

Rust have a big community, lots od dedicated servers and mods. I got interested in modding aspect, so I downloaded and installed a local dedicaded server powered by [Oxide](http://oxidemod.org/downloads/oxide-for-rust.1659/). I decided to use a linux server for this so I set it up with [LGSM](https://gameservermanagers.com/) to decrease amount of possible problems (I'll make a post about it some day). 

Then I became aware of somewhat annoying problem - there's no easy way of editing/uploading/testing the mods. The scripts are written in c# and compiled at runtime (yes, you can reload a mod without restarting the server). Most of admins/devs are using filezilla for ssh connection and notepad++ to edit the scripts. Then RustAdmin or Rusty (popular Rust server tools) to reload the mod by RCON command. Oh, so crude.

So I decided to make my own Rust Server Manager. I want something accessible with normal web browser, scripts editor with highlighting, easy downloading and reloading mods. Something safe, without having to do all the firewall-admin-magic. Something easy like Wordpress, so I can browse mods and install them with one click. 

It's a great chance for some self-development. I'll go with Python+JS combo as I'm not proficient with those. JS because it's necessary to make a decent front-end (also I can consult my wife :P) and Python because it seems perfect for managing game server with its flexibility in connecting different programming languages into one application and making quick scripts. But wait - there's more! I set up this jekyll blog and now I'm learning new possibilities with jekyll, markup and github pages!

'I'm going on an adventure'!