## INCATIVE (temporary)
School21 stopped using slack and moved on to rocket chat. There will be a new version when I have time.
TODO: features like showing freeable memory size, ability to clean selectively with some simple cli.

## PR are welcome.

# iMac cache cleaner script

A simple yet efficient cache cleaner for iMacs at programming school 21 or school 42.
Disk space you get during your studies may fill up really fast, this script helps to get some free disk space without losing necessary data.



# Usage/Examples
## copy and paste below code to your terminal, hit enter:
If asked for confirmation, hit y (yes).
```bash

rm -rf ~/Library/Caches/*

rm -rf ~/Library/42_cache

rm -rf ~/Library/Application\ Support/Slack/Service\ Worker/CacheStorage/

rm -rf ~/Library/Application\ Support/Slack/Cache/

rm -rf ~/Library/Application\ Support/Slack/Code\ Cache/
```

As easy as that 🤷

# Screenshots
### BEFORE:
![BEFORE](https://github.com/azeek21/school21_mac_cache_cleaner/blob/main/berfore.png)
### AFTER:
![AFTER](https://github.com/azeek21/school21_mac_cache_cleaner/blob/main/after.png)

