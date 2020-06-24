# Purification

> Purity purified by purification - even more minimal and fast Zsh prompt

## Overview

Most prompts are cluttered, ugly and slow. I'm not sure mine is better, but I like it anyway!

### Why?

* I needed some `git` infos to remind me where the heck is my code? Oh yeah my stash is full.
* I don't like cluttered Zsh framework anymore. I needed something without any dependency I could modify myself easily when I'm bored.
* There is the Greek lambda letter in your prompt to represent a branch, to teach you that everything can be build from Lambda, and to remind you that Half Life is a great game.

## Install

1. Download `prompt_purification_setup` in a folder.
2. Add the folder path in your fpath (in your `zshrc`): `fpath=(/the/folder/where/there/is/the/prompt $fpath)`
3. Autoload it in your `zshrc`: `autoload -Uz prompt_purification_setup && prompt_purification_setup`
4. You don't like it? Go to hell! You can modify it, too.

## License

[MIT](http://opensource.org/licenses/MIT)
