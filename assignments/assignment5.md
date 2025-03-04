## Password Policy Enforcement Script

### Problem:

> Weak user passwords can be exploited in brute-force attacks.

### Your Task:

Create a BASH script that:

- Audits `/etc/shadow` to check password expiration policies and identifies:

  - Users with weak or empty passwords
  - Users whose passwords have expired
  - Users with no password expiration set

- Forces affected users to update their passwords immediately using `passwd`
- Logs the results into a file named `password_audit-YYYYMMDD_HHMMSS.txt`
- Saves the log file in a directory named `password_audit`
- Redirects errors to `password_audit_error_log.txt` inside the same directory
- Provides user feedback, displaying affected users and the actions taken

**Note**

- Ensure the script is run as `root`: if the user is not `root`, the script should display a message and exit.
- Ensure the script is executable so it can be run with `./script_name.sh`
