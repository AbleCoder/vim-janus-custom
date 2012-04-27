vim-janus-custom
==========

This holds my custom janus .vimrc.* files as well as a janus dir that
holds submodules for git plugins I use.

## Usage

1. Install Vim and [janus](https://github.com/carlhuda/janus)
  
1. Install this font for proper powerline symbols: [VeraMono-Powerline.ttf](https://github.com/gbuntu127/gfonts/blob/master/VeraMono-Powerline.ttf)

1. Clone this repo and init submodules:

  ```
  git clone https://AbleCoder@github.com/AbleCoder/vim-janus-custom.git
  cd vim-janus-custom
  git submodule init
  git submodule update
  ```

1. Create symbolic links

  ```
  ln -s `pwd`/gvimrc.after ~/.gvimrc.after
  ln -s `pwd`/gvimrc.before ~/.gvimrc.before
  ln -s `pwd`/vimrc.after ~/.vimrc.after
  ln -s `pwd`/vimrc.before ~/.vimrc.before
  ln -s `pwd`/janus ~/.janus
  ```

1. Profit!!!
