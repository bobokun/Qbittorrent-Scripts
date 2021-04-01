# Qbittorrent-Scripts

## DEPRECATED - The scripts in this repo are no longer updated/maintained. Please use our new script which adds a lot more features! Found here [Qbit Management](https://github.com/StuffAnThings/qbit_manage)

## Please note that these scripts are tested by me for my use cases.  They very well may work for you but I have not thoroughly tested these scripts under all conditions.  Please test and use at your own risk.

# Prerequisites

Make sure to have the latest version of qbittorrent-api installed. `pip3 install qbittorrent-api`

### qbt_remove_unregistered_torrents

This script removes any unregistered torrents from Qbittorrent

### qbt_autotag_torrents

This script will automatically add tags to torrents based on tracker url from Qbittorrent. Please edit the get_tags function to suit your needs.

### qbt_mass_edit_tracker

This script will mass edit your existing tracker URL and replace it with a new url

## Usage

Create a new User script and paste script text in

### Example Cron Schedules

Cron schedule to run script every morning at 5:00am

```bash
0 5 * * *
```

Cron schedule to run script every Monday morning at 5:00am

```bash
0 5 * * 1
```

Cron schedule to run script every morning at 5:00am except Monday

```bash
0 5 * * 0,2-6
```
