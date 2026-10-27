# Pi Backups

Pi Backups is a small personal tool, used by one person (its owner), that copies encrypted backups of the owner's own home server to the owner's own Google Drive.

- **What it does:** once a day, a script on the owner's Raspberry Pi creates database dumps and a copy of its configuration, encrypts them with [restic](https://restic.net/), and uploads them to a folder in the owner's Google Drive using [rclone](https://rclone.org/).
- **Who uses it:** only the owner. It is not offered to the public and has no other users.
- **Google access:** the app asks for access to the owner's Google Drive so that it can write and read the backup folder. It does nothing else with the account.

See the [privacy policy](PRIVACY.md).

Contact: open an issue on this repository.
