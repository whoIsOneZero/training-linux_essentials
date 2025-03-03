## Scheduled Log Cleanup and Archiving

- **Problem:** Large log files can fill up storage, causing system performance issues.
- **Solution:** Create a **cron job script** that compresses and archives logs from `/var/log/` older than a specified time, moves them to a backup location, and deletes unnecessary logs to free up space.
