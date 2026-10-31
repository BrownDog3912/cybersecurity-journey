# OverTheWire Bandit

## Note:
I do not paste any passwords from levels in here.


## Levels 0-5
 ### What I did
 - Connected over SSH on port 2220
 - Read files that contained spaces in the filename
 - Read files that started with a -
 - Used file to identify what a file contains before I open it

### What I learned
- `file` identifies what a file contains before I open it
- `./` and `--` stop a leading dash being read as an option
- Wildcards like `./*` act on many files at once
- `/home` holds each user's home directory, and `~` is a shortcut to mine

  ### Mistakes
  - Ran cat ./* on binary files and messed up my terminal. I fixed it with `reset` 
