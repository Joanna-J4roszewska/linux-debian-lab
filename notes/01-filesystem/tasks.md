# 01 – Filesystem basics

Format: Task → Command → What happened / What I learned

## Navigation (ls, cd, pwd)
1. Check where you are right after opening the terminal.
   - Command: `pwd`
      - Result: `/home/user/documents`

      ![pwd output](../../screenshots/01-filesystem/pwd.png)

2. List files in your home directory, including hidden ones.
   - Command: `ls -a`
      - Result: `files including hidden ones`

      ![pwd output](../../screenshots/01-filesystem/pwd2.png)

4. List files with details (permissions, size, date) in human-readable sizes.
 * Command: `ls -l`
   * What it does: lists files with details (permissions, owner, size, date)
   * Note: the date shown by `ls -l` is the last modification time, not the creation time. `ls` doesn't show when a file was created by default.
* Command: `ls -la`
   * What it does: lists all files, including hidden ones, with details
* Command: `ls -lah`
   * What it does: same as `ls -la`, but with human-readable sizes (K, M, G)

     ![pwd output](../../screenshots/01-filesystem/3.png)
     
6. Go to `/etc`, check your location, then return home in the shortest way possible.
* Command: `cd /etc`
   * What it does: moved me to the `/etc` directory
* Command: `pwd`
   * What it does: showed my current location
   * Result: `/etc`
* Command: `cd`
   * What it does: moved me back to my home directory (shortest way)

     ![pwd output](../../screenshots/01-filesystem/4.png)

8. Go up one directory, then go back to the previous directory with one short command.
9. What's the difference between an absolute and a relative path? Show one example of each with `cd`.
****
