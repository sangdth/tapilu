# Vue Snippets for Vim

A Vim snippet library for Vue.

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

## Installation

Using [Vundle](https://github.com/VundleVim/Vundle.vim):

```vim
" Vim Vue Snippets
Plugin 'sangdth/vim-vue-snippets'

" Ultisnips (required)
Plugin 'SirVer/ultisnips'

" Trigger configuration (Optional)
" let g:UltiSnipsExpandTrigger="<C-l>"
```

## Usage
In a `.vue` file, type a trigger name while in Insert mode, then press Ultisnips trigger key. In my case I have it mapped to `<C-l>`.

Use `<C-j>` and `<C-j>` to jump to next/previous tabstop.

## Snippets
Note: `→` is your expand trigger key.

#### Layout

| Trigger             | Content |
| ------------------: | ------- |
| `vsc→`              | Vue Single file Component |
