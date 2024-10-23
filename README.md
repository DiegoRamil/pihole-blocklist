# Pihole Blocklist 
This repository automatically updates the block list by using a cron in a github action, each update occurs at 00:00 UTC.

## How to use it
In you pihole, navigate to the adlists tab `<ip:port>/admin/groups-adlists.php` and add the blobs that you want by typing `https://github.com/DiegoRamil/pihole-blocklist/blob/main/<blob-that-you-want>.txt`, next update your pihole adlist to include the ones that you create now by navigating to `<ip:port>/admin/gravity` and click in update gravity.
