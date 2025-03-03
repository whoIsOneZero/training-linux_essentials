## Assignment 1:

**Problem:**  
Write a script that

- Scans the `/etc/passwd` file and extracts a list of all **system users** (UID < 1000) and **normal users** (UID ≥ 1000).
- Saves each category into separate files (`system_users.txt` and `normal_users.txt`).

**Tips:**

- `cut`, `awk`, `grep`
- `if` conditions
- File redirection (`>`, `>>`)
