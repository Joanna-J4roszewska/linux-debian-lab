# 05 – Backup & restore

Format: Task → Command → What happened / What I learned

### Archives with tar

1. Pack the `lab` folder into a single archive file `lab.tar`.
   * Command:
     * What it does:

2. Do the same, but compressed, as `lab.tar.gz`. Compare the size of both archives.
   * Command:
     * What it does:

3. List what's inside `lab.tar.gz` without unpacking it.
   * Command:
     * What it does:

4. Unpack `lab.tar.gz` into a new folder `restore_test` and check that everything is there.
   * Command:
     * What it does:

5. Restore just one file from the archive, not the whole thing.
   * Command:
     * What it does:

### Keeping permissions and dates

6. Create a file with special permissions (e.g. 600), back it up, restore it, and check whether the permissions and the date stayed the same.
   * Command:
     * What it does:

### Backups with a date in the name

7. Create a backup whose file name contains today's date, e.g. `lab_2026-11-07.tar.gz`, without typing the date by hand.
   * Command:
     * What it does:

### Syncing folders with rsync

8. Copy `lab` to `backup_lab` using rsync. Then change one file in `lab` and run rsync again. What gets copied the second time?
   * Command:
     * What it does:

9. Delete a file in `lab` and sync again. Does it disappear from the backup too? Which option controls that, and why can it be dangerous?
   * Command:
     * What it does:

### Backing up important system files

10. Back up the whole `/etc` folder (system configuration) into an archive. Why do you need sudo for that?
    * Command:
      * What it does:

11. Before editing a config file, make a quick copy of it, edit the original, then restore the copy.
    * Command:
      * What it does:

### Automating backups

12. Write a small bash script that creates a dated backup of `lab` in a `backups` folder.
    * Command:
      * What it does:

13. Schedule the script with cron to run every day at 2:00. Check that the cron entry is saved.
    * Command:
      * What it does:

14. Make the script keep only the 7 newest backups and delete older ones.
    * Command:
      * What it does:

### Testing the backup

15. Scenario: "a user deleted an important folder". Delete `lab` on purpose and restore it from your newest backup. Check that the files and permissions are correct.
    * Command:
      * What it does:

Summary:
