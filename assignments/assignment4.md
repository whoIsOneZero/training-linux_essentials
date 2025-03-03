## Automated File Permission Hardening

- **Problem:** Incorrect file permissions can allow unauthorized access to sensitive data.
- **Solution:** Develop a script that scans system directories for files with **insecure permissions** (world-writable, no owner, etc.), lists them, and prompts the administrator to apply secure permissions (`chmod` and `chown`).
