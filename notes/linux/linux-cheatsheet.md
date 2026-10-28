# Linux cheatsheet

## Navigation
- `pwd` prints the current directory
- `cd <dir>` moves into a directory, `cd ..` moves up, `cd` alone goes home
- `ls -la` lists everything, including hidden files, in long format

## Reading files
- `cat <file>` prints a file
- `file <name>` shows what kind of data a file holds (check before using `cat`)

## Filenames
- Spaces: use quotes, backslashes, or Tab completion
- Leading dash: use `./name` or `-- name`

## Wildcards
- `*` means "everything here", e.g. `file ./*`

## Terminal
- `reset` fixes a scrambled terminal

## Mistakes and lessons
- `cat` on binary files prints garbage, so identify with `file` first
