Alpharized
==========

[Alpha](http://en.wikipedia.org/wiki/Alpha_Centauri)rized is oh-my-zsh theme optimized to work with [solarized](http://ethanschoonover.com/solarized) dark. It's a modified version of the [avit theme](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/avit.zsh-theme).

![screenshot](https://photos-4.dropbox.com/t/0/AADZ7UY7zmwd3LabR3LHChdttiVPSgGtmrlQX8m4hKtkxA/12/9909902/png/1024x768/3/1401159600/0/2/themescreen.png/hSpnCbGCo44yVy98IaXhGl3jHtXZaiHrrKNuGE5O43g)

It uses the following symbols for git:

* dirty = ✗
* clean = ✔
* added = ✚
* modified = ⚑
* deleted = ✖
* renamed = ▴
* unmerged = §
* untracked = ◒

And it will display the vi status and ruby version if those plugins [vi-mode and rvm](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins-Overview) are active.

## How to install

1. Download the theme into oh-my-zsh's custom themes directory:`$ mkdir -p $ZSH_CUSTOM/themes && curl https://raw.githubusercontent.com/NicoSantangelo/Alpharized/master/alpharized.zsh-theme -o $ZSH_CUSTOM/themes/alpharized.zsh-theme`
2. Set the theme in your .zshrc file: `ZSH_THEME="alpharized"`
3. For the nice colors, use [Solarized Dark](http://ethanschoonover.com/solarized) the screenshot is using the color scheme for iTerm2.

Thanks [@Jinik](https://github.com/Jinik) for the name!