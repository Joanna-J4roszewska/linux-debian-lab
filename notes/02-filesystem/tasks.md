# 02 – Filesystem basics

Format: Task → Command → What happened / What I learned

## Creating & reading (touch, echo, mkdir, cat)

1. Create an empty file `test.txt` and confirm it exists.
   * Command: `touch test.txt`
     * What it does: created an empty file
   * Command: `ls`
     * Result: `test.txt` is listed (white = file)
   * Command: `rm test.txt`
     * What it does: deleted the file
   * Learned: at first I used `mkdir test.txt` by mistake. It created a directory
     named `test.txt` (shown in blue). The `.txt` in a name doesn't make it a file.
     I removed it with `rmdir` and used `touch` instead.

   ![touch, ls and rm output](../../screenshots/02-filesystem/7.png)
   
3. Run `touch` on the same file again. What changed?
4. Create three empty files with one command: `a.txt`, `b.txt`, `c.txt`.
5. Print "Hello Debian" on the screen.
6. Write "Hello Debian" into a file `hello.txt`.
7. Add a second line "Learning Linux" to `hello.txt` without deleting the first one.
8. Overwrite `hello.txt` with just "New content". What happened to the old lines?
9. Create a folder `lab`.
10. Create the path `lab/docs/old` with one command.
11. Create three folders inside `lab` with one command: `backup`, `temp`, `logs`.
12. Display the contents of `hello.txt`.
13. Display `/etc/os-release` and find the Debian version.
14. Display two files at once with one `cat` command.
15. Display `hello.txt` with line numbers.
16. Join `a.txt` and `hello.txt` into a new file `joined.txt` using `cat`.

## Scenario: quick note file
Inside `lab/docs`, create a file `notes.txt` containing three lines:
your name, today's date (taken from the system, not typed by hand),
and the current directory path (also from the system).
Then display it to confirm
