# Cobra

Dark colorscheme for C/C++/x86_64 development.


## Installation

It is recommended to use Vim's native package management. See *:help packages* for details.

* clone this repo into `.vim/pack/*/opt/cobra` or `.vim/pack/*/start/cobra`

Add the colorscheme in `.vimrc` or from a running vim session.

```vim
`colorscheme cobra`
```

## Customization

A `cursorline` is enabled by default to set the active line's background color and column number. This can be disabled:

```vim
set nocursorline
```

x86
---

For x86_64, you may need to indicate to vim the assembly flavor to get syntax highlighting.

```vim
let asmsyntax="nasm"
```
  
