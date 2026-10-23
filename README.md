# tmux configuration

A personal tmux setup for keyboard-driven terminal sessions. It uses Alt+B as the prefix, vi-style copy mode, mouse support, true-color terminal settings, pane and window shortcuts, and Catppuccin and CPU status plugins with a Cyberdream-inspired palette.

## Install

Install tmux. Copy `tmux.conf` to `~/.tmux.conf`, then reload it from a running session:

~~~sh
tmux source-file ~/.tmux.conf
~~~

The configuration uses TPM (Tmux Plugin Manager) for its plugins. Install TPM and press Alt+B followed by Shift+I inside tmux to install them. Clipboard copy bindings call `xclip` on Linux. Some shortcuts also expect the `f` command and `lazygit` to be available in your shell.
