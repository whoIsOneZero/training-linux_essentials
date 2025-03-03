## Password Policy Enforcement Script

- **Problem:** Weak user passwords can be exploited in brute-force attacks.
- **Your Task:** Create a BASH script that audits `/etc/shadow` to check password expiration policies, identifies users with weak or empty passwords, and forces them to update their passwords using `passwd`