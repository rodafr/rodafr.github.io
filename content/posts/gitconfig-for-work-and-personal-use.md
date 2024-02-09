+++
title = 'Gitconfig for Work and Personal Use'
date = 2024-02-09T15:36:10+01:00
tags = ["work", "git", "personal"]
+++

When writing blog posts from WSL on my work machine it's easy to mix up personal and work git user settings. For instance I have pushed a couple of commits (and "doxxed" myself) on this blog a time or two.  
Don't worry though, I have rewritten history using [LazyGit](https://github.com/jesseduffield/lazygit)'s awesome functionality to change the author back to my personal credentials.


Anyway, I found this guide to set up separate .gitconfig files for work and play: [GitGuardian](https://blog.gitguardian.com/8-easy-steps-to-set-up-multiple-git-accounts/)

Assuming you use ssh to connect to remote repos (as you should), it's just a few lines to set different git users for different directories. Neat!
