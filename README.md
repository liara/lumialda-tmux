# lumialda-tmux


A basic tmux configuration with different color themes and system status
information to get you started, based on [lumialda](https://github.com/meskarune/lumialda) 
for GNU Screen.

![screenshot](https://raw.github.com/liara/lumialda-tmux/master/screenshot.png)

## Installation:

1. Clone this repository
    ```git clone https://github.com/liara/lumialda-tmux.git```
2. Move the contents of `scripts` to a directory in your `PATH`, probably `~/bin`. 
   To add `~/bin` to `PATH` add `export PATH=$HOME/bin:${PATH}` to your shell 
   startup file .zshrc, .bashrc, .kshrc or else.
3. Move a `*tmux.conf` configuration file to your home
   ```cp cyantmux.conf ~/.tmux.conf```
4. Alternatively you can specify which configuration file to use
    ```tmux -f cyantmux.conf```
5. Modify the configuration file to fit your needs, add plugins or else.

## Resources:

- [Tmux](https://tmux.github.io/)
- [Gentoo - Wiki example](https://wiki.gentoo.org/wiki/Tmux#Wiki_example)
- [Dotshare.it - Tmux](http://dotshare.it/category/terms/tmux/)
- [tmux-networkspeed](https://github.com/gryftir/tmux-networkspeed)
- [A tmux Primer](https://danielmiessler.com/study/tmux/)
- [tmux-plugins](https://github.com/tmux-plugins)
