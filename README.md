# Reload tmux Configuration

This guide explains how to reload your tmux configuration file without restarting tmux.

## Key Binding

Use the following key combination to reload the tmux configuration:

prefix + q

This binding reloads the configuration from:

~/.config/tmux/tmux.conf

## Configuration Path

If your tmux configuration file is located in a different path, such as:

~/.tmux.conf

make sure to update the path in the binding so it points to the correct configuration file.

**Note:** This has native support for vim-tmux-navigator.
