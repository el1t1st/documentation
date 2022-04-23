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
