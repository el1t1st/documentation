# Neovim Patters and Workflows

<!-- vim-markdown-toc GFM -->

- [How to search and replace a text in a file?](#how-to-search-and-replace-a-text-in-a-file)
- [How to copy paste a block in Visual Mode?](#how-to-copy-paste-a-block-in-visual-mode)
- [How to copy paste a line in Normal Mode?](#how-to-copy-paste-a-line-in-normal-mode)
- [How to open a file in a vertical window next to the current opened file?](#how-to-open-a-file-in-a-vertical-window-next-to-the-current-opened-file)
- [How to navigate between split windows?](#how-to-navigate-between-split-windows)
- [What is a faster way to save the contents of a file instead of `:w`?](#what-is-a-faster-way-to-save-the-contents-of-a-file-instead-of-w)
- [What is a faster way to save the changes and quit?](#what-is-a-faster-way-to-save-the-changes-and-quit)
- [How can you move you cursor to the middle of the window?](#how-can-you-move-you-cursor-to-the-middle-of-the-window)

<!-- vim-markdown-toc -->

## How to search and replace a text in a file?

`:%s/text that needs to be changed/new text/g`

- `%` means the whole file
- `s` means search
- `g` means every instace

## How to copy paste a block in Visual Mode?

1. Set the curson at the beginning of the text you want to copy.
2. `v` to enter Visual Mode
3. use h j k l to select the text you want to copy
4. `y` to yank (copy) to clipboard
5. move cursor to where you want to past with h j k l
6. `p` to paste the contents of the clipboard

## How to copy paste a line in Normal Mode?

1. Move cursor to the line you want to copy
2. `yy` to copy
3. Move curson to where you want to paste
4. `p` to paste

## How to open a file in a vertical window next to the current opened file?

1. `<C-n>` to open the Nerdtree Explorer
2. Use h j k l to navigate to the file you want to open
3. `<C-v>` to open the file in vertical split

> To move from one window to the other use `<C-w> h l

## How to navigate between split windows?

`<C-w> h j k l`

## What is a faster way to save the contents of a file instead of `:w`?

`<C-s>`

## What is a faster way to save the changes and quit?

`ZZ`

## How can you move you cursor to the middle of the window?

`zz`
