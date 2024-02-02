# Snapshot

A Bash script to generate snapshots of directories and also supports backing up MySQL databases. This tool uses [rclone](https://github.com/rclone/rclone) and [restic](https://github.com/restic/restic).
List of cloud/storage providers currently supported by rclone can be found [here](https://github.com/rclone/rclone#storage-providers).

## Features
* Configurable retention policy. (using restic's policies)
* Uses rclone.
* Pushover notifications.
