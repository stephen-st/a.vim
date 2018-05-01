# "Alternate" Vim Plugin

Alternate between source and header files quickly.

This is a personal fork of the original [vim-scripts/a.vim][source] plugin, including some
desirable updates for general use:

* Removed `leader` mappings
* Added support for `.cc` and `.hh` C++ extensions

## Setup

Invoke the `:A` command in vim/neovim or map it as a key in `~/.vimrc`:

```
map <F2> :A<CR>
```

[source]: https://github.com/vim-scripts/a.vim
