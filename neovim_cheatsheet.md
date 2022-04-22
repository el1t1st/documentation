# Exiting

| Command    | Description                      |
| ---------- | -------------------------------- |
| `:qa`      | Close all files                  |
| `:qa!`     | Close all files, abandon changes |
| `:w`       | Save                             |
| `:wq / :x` | Save and close file              |
| `:q`       | Close file                       |
| `:q!`      | Close file, abandon changes      |
| `ZZ`       | Save and quit                    |
| `ZQ`       | Quit without checking changes    |

# Editing

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

# Exiting insert move

| Command        | Description                                 |
| -------------- | ------------------------------------------- |
| `Esc or <C-[>` | Exit insert mode                            |
| `<C-C>`        | Exit insert mode, and abort current command |

# Visual mode

| Command | Description             |
| ------- | ----------------------- |
| `v`     | Enter visual mode       |
| `V`     | Enter visual line mode  |
| `<C-V>` | Enter visual block mode |

## In visual mode

| Command  | Description           |
| -------- | --------------------- |
| `d or x` | Delete selection      |
| `s`      | Replace selection     |
| `y`      | Yank selection (Copy) |

# Navigating

| Command | Description    |
| ------- | -------------- |
| `h`     | Left           |
| `l`     | Right          |
| `j`     | Down           |
| `k`     | Up             |
| `<C-U>` | Half-page up   |
| `<C-D>` | Half-page down |

## Navigating words

| Command | Description          |
| ------- | -------------------- |
| `b`     | Previous word        |
| `w`     | Next word            |
| `ge`    | Previous end of word |
| `e`     | Next end of word     |

## Navigating line

| Command    | Description                    |
| ---------- | ------------------------------ |
| `0` (zero) | Start of line                  |
| `^`        | Start of line after whitespace |
| `$`        | End of line                    |
