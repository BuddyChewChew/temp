📌 EPGS are hit and miss right now. The source for the EPGs is having server problems. Hopefully to be fixed soon.

1.  Click on the desired `.m3u` file (e.g., `plutotv_us.m3u`).
2.  On the file page, click the **"Raw"** button.
3.  Copy the URL from your browser's address bar.

The URL will look like:
https://raw.githubusercontent.com/BuddyChewChew/app-m3u-generator/refs/heads/main/playlists/FILENAME.m3u


*Replace `FILENAME.m3u` with the specific playlist file you want (e.g., `plex_all.m3u`, `plex_us.m3u`).*

Paste this complete raw URL into your IPTV player's M3U playlist source field. The player should automatically fetch the playlist and the EPG data specified in the `url-tvg` tag.

*(Note: The `_us` versions contain channels specific to the US region, while `_all` versions attempt to combine channels from multiple available regions, grouped by region/country.)*
