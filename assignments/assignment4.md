## Assignment 4

**Problem:**  
Write a script that:

- Checks all users in `/etc/shadow` and identifies **accounts that have not changed their passwords in the last 90 days.**
- Forces a password change for such users by setting their last password change date to today
- Stores a log entry of affected users in a file named `password_reset_log-YYYYMMDD_HHMMSS.txt`
- Saves the log file in a directory named `password_policy`
- Prints a message indicating where the output file is saved
- Redirects errors to a log file named `password_policy_error_log`.txt in the `password_policy` directory

**Tips:**

- Use the `man` pages
- `while` or `for` loops
- `if` statements
- `chage -l`
- Ensure the script is executable so it can be run with `./script_name.sh`
