## Assignment 3

**Problem:**  
Create a script that:

- Adds a new user (with `useradd`)
- Sets a password for the user (with `passwd`)
- Enforces password expiration so that the user **must change the password on first login**
- Stores a log entry of the created user in a file named `user_creation_log-YYYYMMDD_HHMMSS.txt`
- Saves the log file in a directory named `user_management`
- Prints a message indicating where the output file is saved.
- Redirects errors to a log file `audit_error_log.txt` in the `password_audit directory`.

**Tips:**

- Use the `man` pages
- `read`
- `useradd`, `passwd`
- `chage`
- Ensure the script is executable so it can be run with `./script_name.sh`
