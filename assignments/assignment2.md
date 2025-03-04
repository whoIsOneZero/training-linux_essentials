## Assignment 2:

**Problem:**  
Write a script that:

- Searches `/etc/shadow` and **identifies users who have an empty password field**.
- Outputs only the usernames of such accounts into a file named: `empty_password_users-YYYYMMDD_HHMMSS.txt`
- Stores the output file in a directory named `password_audit`.
- Prints a message indicating where the output file is saved.
- Redirects errors to a log file `audit_error_log.txt` in the `password_audit directory`.

**Tips:**

- Use the `man` pages
- `grep`, `awk`, `cut` (Filtering and Parsing)
- `-z` (Check for empty fields)
- File reading and processing
- Ensure the script is executable so it can be run with `./script_name.sh`
