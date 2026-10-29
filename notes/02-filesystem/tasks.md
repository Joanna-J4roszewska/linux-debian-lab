## Creating & reading (touch, echo, mkdir, cat)

1. Create an empty file `test.txt` and confirm it exists.
2. Run `touch` on the same file again. What changed?
3. Create three empty files with one command: `a.txt`, `b.txt`, `c.txt`.
4. Print "Hello Debian" on the screen.
5. Write "Hello Debian" into a file `hello.txt`.
6. Add a second line "Learning Linux" to `hello.txt` without deleting the first one.
7. Overwrite `hello.txt` with just "New content". What happened to the old lines?
8. Create a folder `lab`.
9. Create the path `lab/docs/old` with one command.
10. Create three folders inside `lab` with one command: `backup`, `temp`, `logs`.
11. Display the contents of `hello.txt`.
12. Display `/etc/os-release` and find the Debian version.
13. Display two files at once with one `cat` command.
14. Display `hello.txt` with line numbers.
15. Join `a.txt` and `hello.txt` into a new file `joined.txt` using `cat`.

## Scenario: quick note file
Inside `lab/docs`, create a file `notes.txt` containing three lines:
your name, today's date (taken from the system, not typed by hand),
and the current directory path (also from the system).
Then display it to confirm
