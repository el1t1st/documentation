# Custom keybindings

# Project

| Command | Description                         |
| ------- | ----------------------------------- |
| `<C-p>` | Open up Projects panel in Telescope |

## NvimTree

| Command          | Description                                          |
| ---------------- | ---------------------------------------------------- |
| `<C-n>`          | Toggle the NvimTree File Explorer                    |
| `<leader>n`      | Find file in NvimTree File Explorer                  |
| `:vs` or `<C-v>` | Edit in newly opened window next (vertical split)    |
| `:sp` or `<C-x>` | Edit in newly opened window above (horizontal split) |
| `<C-t>`          | Edit in new tab                                      |
| `<CR>`           | Edit file                                            |
| `.`              | cd                                                   |
| `a`              | Create new file in the folder you are in             |
| `d`              | Delete a file                                        |
| `r`              | Rename a file                                        |

See the **Working with split screens** below how to navigate and move from one window to the next.

## Telescope

| Command      | Description               |
| ------------ | ------------------------- |
| `<leader>ff` | Find files in Telescope   |
| `<leader>fg` | Live grep in Telescope    |
| `<leader>fb` | Find buffers in Telescope |
| `<leader>fh` | Find help in Telescope    |

## Terminal

| Command | Description               |
| ------- | ------------------------- |
| `<A-t>` | Toggle the Fterm terminal |

## Markdown

| Command      | Description                        |
| ------------ | ---------------------------------- |
| `<leader>md` | Launch the Markdown preview window |

# General keybindings

## Working with split screens

| Command           | Description                                                 |
| ----------------- | ----------------------------------------------------------- |
| `:vs` or `<C-w>v` | Open up a new screen next to the current (horizontal split) |
| `:sp` or `<C-w>s` | Open up a window above the current (vertical split)         |
| `<C-w> h j k l`   | Navigate among the split screens                            |

## Exiting

| Command         | Description                      |
| --------------- | -------------------------------- |
| `:qa`           | Close all files                  |
| `:qa!`          | Close all files, abandon changes |
| `:w` or `<C-s>` | Save                             |
| `:wq / :x`      | Save and close file              |
| `:q`            | Close file                       |
| `:q!`           | Close file, abandon changes      |
| `ZZ`            | Save and quit                    |
| `ZQ`            | Quit without checking changes    |

## Editing

| Command | Description                         |
| ------- | ----------------------------------- |
| `a`     | Append                              |
| `A`     | Append from end of line             |
| `i`     | Insert                              |
| `o`     | Next line                           |
| `O`     | Previous line                       |
| `s`     | Delete char and insert              |
| `S`     | Delete line and insert              |
| `C`     | Delete until end of line and insert |
| `r`     | Replace one character               |
| `R`     | Enter replace mode                  |
| `u`     | Undo changes                        |
| `<C-R>` | Redo changes                        |

## Exiting insert mode

| Command        | Description                                 |
| -------------- | ------------------------------------------- |
| `Esc or <C-[>` | Exit insert mode                            |
| `<C-C>`        | Exit insert mode, and abort current command |

## Visual mode

| Command | Description             |
| ------- | ----------------------- |
| `v`     | Enter visual mode       |
| `V`     | Enter visual line mode  |
| `<C-V>` | Enter visual block mode |

### In visual mode

| Command  | Description           |
| -------- | --------------------- |
| `d or x` | Delete selection      |
| `s`      | Replace selection     |
| `y`      | Yank selection (Copy) |

## Navigating

| Command | Description    |
| ------- | -------------- |
| `h`     | Left           |
| `l`     | Right          |
| `j`     | Down           |
| `k`     | Up             |
| `<C-U>` | Half-page up   |
| `<C-D>` | Half-page down |

### Navigating words

| Command | Description          |
| ------- | -------------------- |
| `b`     | Previous word        |
| `w`     | Next word            |
| `ge`    | Previous end of word |
| `e`     | Next end of word     |

### Navigating line

| Command    | Description                    |
| ---------- | ------------------------------ |
| `0` (zero) | Start of line                  |
| `^`        | Start of line after whitespace |
| `$`        | End of line                    |

### Navigating character

| Command | Description                |
| ------- | -------------------------- |
| `fc`    | Go forward to character c  |
| `Fc`    | Go backward to character C |

### Navigating document

| Command | Description  |
| ------- | ------------ |
| `gg`    | First line   |
| `G`     | Last line    |
| `:n`    | Go to line n |
| `nG`    | Go to line n |

### Navigation of the cursor inside a window

> Todo: this needs to be described differently. This is very useful.

| Command | Description                                                  |
| ------- | ------------------------------------------------------------ |
| `zz`    | Center this line                                             |
| `zt`    | Top this line                                                |
| `zb`    | Bottom this line                                             |
| `H`     | Move to top of the screen **Doesn't seem to work**           |
| `M`     | Move to middle of the screen **Doesn't seem to work**        |
| `L`     | Move to bottom of the screen **Doesn't seem to work either** |

### Navigation of search

| Command | Description                          |
| ------- | ------------------------------------ |
| `n`     | Next matching search pattern         |
| `N`     | Previous matching search pattern     |
| `*`     | Next whole word under the cursor     |
| `#`     | Previous whole word under the cursor |

### Navigation of tab pages

| Command           | Description                    |
| ----------------- | ------------------------------ |
| `:tabedit [file]` | Edit file in new tab           |
| `:tabfind [file]` | Open file if exists in new tab |
| `:tabclose`       | Close current tab              |
| `:tabs`           | List all tabs                  |
| `:tabfirst`       | Go to first tab                |
| `:tablast`        | Go to last tab                 |
| `:tabn`           | Go to next tab                 |
| `:tabp`           | Go to previous tab             |

## Operators

### Usage

Operators let you operate in a range of text (defined by motion). These are performed in normal mode.

| Operator | Motion |
| -------- | ------ |
| `d`      | `w`    |

#### Examples

Combine operators with motions to use them.

| Command              | Description                                 |
| -------------------- | ------------------------------------------- |
| `dd`                 | (repeat the letter) Delete the current line |
| `dw`                 | Delete to the next word                     |
| `db`                 | Delete to the previous word                 |
| `2dd`                | Delete 2 lines                              |
| `dip`                | Delete a text object (inside paragraph)     |
| (in visual mode) `d` | Delete selection                            |

### Operators list

| Command | Description                                          |
| ------- | ---------------------------------------------------- |
| `d`     | Delete                                               |
| `y`     | Yank (Copy)                                          |
| `c`     | Change (Delete then insert)                          |
| `>`     | Indent right                                         |
| `<`     | Indent left                                          |
| `=`     | Autoindent                                           |
| `g~`    | Swap case                                            |
| `gU`    | Uppercase                                            |
| `gu`    | Lowercase                                            |
| `!`     | Filter through external program **check this later** |

## Text objects

### Usage

Text objects let you operate (with an operator) in or around text blocks (objects).

| Operator | [i]nside or [a]round | Text object |
| -------- | -------------------- | ----------- |
| `v`      | `i`                  | `p`         |

#### Examples

| Command     | Description                        |
| ----------- | ---------------------------------- |
| `vip`       | Select paragraph                   |
| `vipipipip` | Select more                        |
| `yip`       | Yank inner paragraph               |
| `yap`       | Yank paragraph (including newline) |
| `dip`       | Delete inner paragraph             |
| `cip`       | Change inner paragraph             |

#### Text objects

| Command   | Description      |
| --------- | ---------------- |
| `p`       | Paragraph        |
| `w`       | Word             |
| `s`       | Sentence         |
| `[ ( { <` | A [],(),{} block |
| `' " `    | A quoted string  |
| `b`       | A block `[(`     |
| `B`       | A block `[{`     |
| `t`       | An XML tag block |

#### Diff

| Command                        | Description                           |
| ------------------------------ | ------------------------------------- |
| `gvimdiff file1 file2 [file3]` | See differences between files, in HMI |

## Misc

### Folds

| Command      | Description               |
| ------------ | ------------------------- |
| `zo` or `zO` | Open                      |
| `zc` or `zC` | Close                     |
| `za` or `zA` | Toggle                    |
| `zv`         | Open folds for this line  |
| `zM`         | Close all                 |
| `zR`         | Open all                  |
| `zm`         | Fold more (foldlevel +=1) |
| `zr`         | Fold less (foldlevel -=1) |
| `zx`         | Update folds              |

Uppercase ones are recursive (zO means open recursively).

### Windows

| Command         | Description                        |
| --------------- | ---------------------------------- |
| `z{height}<Cr>` | Resize pane to {height} lines tall |

### Tags

| Command              | Description                                     |
| -------------------- | ----------------------------------------------- |
| `:tag Classname`     | Jump to the first definition of Classname       |
| `<C-]>`              | Jump to definition                              |
| `g]`                 | See all definitions                             |
| `<C-T>`              | Go back to last tag                             |
| `<C-O>` `<C-I>`      | Back/Forward                                    |
| `:tselect Classname` | Find definitions of Classname                   |
| `:tjump Classname`   | Find definitions of Classname (auto-select 1st) |

### Useful to know

| Command        | Description                                       |
| -------------- | ------------------------------------------------- |
| `.`            | Repeat last command                               |
| `]p`           | Paste under the current indentation level         |
| `:set ff=unix` | Convert Windows line endings to Unix line endings |

### Command line

| Command      | Description                               |
| ------------ | ----------------------------------------- |
| `<C-R><C-W>` | Insert current word into the command line |
| `<C-R>"`     | Paste from " register                     |
| `<C-X><C-F>` | Auto-completion of path in insert mode    |

### Text alignment

`:center [width]` \
`:right [width]` \
`:left`

### Exiting with an error

`:cq` \
`:cquit`

### Navigation

| Command    | Description             |
| ---------- | ----------------------- |
| `%`        | Nearest matching {[()]} |
| `[( [{ [<` | Previous ( or { or <    |
| `])`       | Next                    |
| `[m`       | Previous method start   |
| `[M`       | Previous method end     |

### Jumping

| Command | Description                  |
| ------- | ---------------------------- |
| `<C-O>` | Go back to previous location |
| `<C-I>` | Go forward                   |
| `gf`    | Go to file in cursor         |

### Counters

| Command | Description      |
| ------- | ---------------- |
| `<C-A>` | Increment number |
| `<C-X>  | Decrement number |

### Case

| Command | Description                        |
| ------- | ---------------------------------- |
| `~`     | Toggle case (Case => cASE)         |
| `gU`    | Uppercase                          |
| `gu`    | Lowercase                          |
| `gUU`   | Uppercase current line (also gUgU) |
| `guu`   | Lowercase current line (also gugu) |

This works in visual and normal modes.

### Marks

| Command     | Description                                          |
| ----------- | ---------------------------------------------------- |
| `^          | Last position of cursor in insert mode               |
| `.          | Last change in current buffer                        |
| `"          | Last exited current buffer                           |
| `0          | In last file edited                                  |
| ''          | Back to line in current buffer where jumped from     |
| ``          | Back to position in current buffer where jumped from |
| `[          | To beginning of previously changed or yanked text    |
| `]          | To end of previously changed or yanked text          |
| `<          | To beginning of last visual selection                |
| `>          | To end of last visual selection                      |
| `ma`        | Mark this cursor as a                                |
| `a          | Jump to the cursor position a                        |
| 'a          | Jump to the beginning of the line with position a    |
| `d'a`       | Delete from current line to line of mark a           |
| d`a         | Delete from current position to line of mark a       |
| `c'a`       | Change text from current line to line of a           |
| y`a         | Yank text from current position to position of a     |
| `marks`     | List all current marks                               |
| `:delm a`   | Delete mark a                                        |
| `:delm a-d` | Delete marks a, b, c, d                              |
| `:delm abc` | Delete marks a, b, c                                 |

### Spell checking

| Command                      | Description                                                 |
| ---------------------------- | ----------------------------------------------------------- |
| `:set spell spelllang=en_us` | Turn on US English spell checking                           |
| `]s`                         | Move to next misspelled word after the cursor               |
| `[s`                         | Move to previous misspelled word before the cursor          |
| `z=`                         | Suggest spellings for the word under/after the cursor       |
| `zg`                         | Add word to spell list                                      |
| `zw`                         | Mark word as bad/mispelled                                  |
| `zu` `<C-X>`(insert mode)    | Suggest words for bad word under the cursor from spellfile. |
