## Assignment 1:

**Problem:**  
Write a script that

- Scans the `/etc/passwd` file and extracts a list of all **system users** (UID < 1000) and **normal users** (UID ≥ 1000).
- Saves each category into separate files with a timestamp in the filename

  - `system_users-YYYYMMDD_HHMMSS.txt`
  - `normal_users- YYYYMMDD_HHMMSS.txt`

- Stores the output files are stored in a directory named `user_reports`.
- Prints a message indicating where the output files are saved.
- Redirects errors to a log file `error_log.txt` in the `user_reports` directory.

**Tips:**

- Use the `man` pages
- `cut`, `awk`, `grep`
- `if` conditions
- File redirection (`>`, `>>`)
- Ensure the script is executable so it can be run with `./script_name.sh`
