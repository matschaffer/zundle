## About

[Zundle] is short for **Z**shb**undle** and is a [Zsh] plugin manager.

## Quick start

1. Setup [Zundle]:

     ```
     $ git clone https://github.com/matschaffer/zundle.git ~/.zsh/bundle/zundle
     ```

2. Configure bundles:

     Sample `.zshrc`:

     ```sh
     source "$HOME/.zsh/bundle/zundle/rc"

     Bundle 'matschaffer/zsh-git'
     Bundle 'matschaffer/zsh-rvm'
     Bundle 'matschaffer/zsh-theme-gnzh'
     ```

3. Install configured bundles:

     ```
     $ source "$HOME/.zshrc"
     $ BundleInstall
     ```

     Installing requires [Git] and triggers [Git clone](http://gitref.org/creating/#clone) for each configured repo to `~/.vim/bundle/`.

## Why Zundle

[Zundle] allows to:

- keep track and configure your scripts right in `.zshrc`
- install configured scripts (aka bundle)
- update configured scripts

## People Using Zundle

   * [matschaffer's zshrc](https://github.com/matschaffer/zsh-matschaffer/blob/master/zshrc)

   If you have an interesting example, feel free to send a pull request with link to your config. Thanks!

## FAQ

see [wiki](/matschaffer/zundle/wiki)

## Inspiration and ideas from

* [vundle]
* [oh-my-zsh]

[Zundle] is a work in progress so any ideas/patches appreciated

[Zundle]:https://github.com/matschaffer/zundle
[Zsh]:http://www.zsh.org
[Git]:http://git-scm.com

[vundle]:https://github.com/gmarik/vundle
[oh-my-zsh]:https://github.com/robbyrussell/oh-my-zsh
