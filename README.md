## About

[Zundle] is short for **Z**shb**undle** and is a [Zsh] plugin manager.

## Quick start

1. Setup [Zundle]:

     ```
     $ git clone http://github.com/matschaffer/zundle.git ~/.zsh/bundle/zundle
     ```

2. Configure bundles:

     Sample `.zshrc`:

     ```sh
     source "$HOME/.zsh/bundle/zundle/rc"

     Bundle 'matschaffer/zsh-matschaffer'
     ```

3. Install configured bundles:

     ```
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

## Also

* Zundle was developed and tested with [Zsh] 7.3 on `OSX`, `Linux` and `Windows`
* Zundle tries to be as [KISS](http://en.wikipedia.org/wiki/KISS_principle) as possible

## TODO:

[Zundle] is a work in progress so any ideas/patches appreciated

* Build repo of useful oh-my-zsh stuff
* make it rock!

[Zundle]:http://github.com/matshaffer/zundle
[Zsh]:http://www.zsh.org
[Git]:http://git-scm.com
