## User Activity and Command History Monitoring

- **Problem:** Malicious users may try to cover their tracks by clearing history or modifying logs.
- **Your Task:** Write a script that continuously monitors `.bash_history` files for deletions, logs all executed commands to a secure location, and prevents users from executing `history -c`.
