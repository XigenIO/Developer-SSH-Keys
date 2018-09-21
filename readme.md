# SSH

## Crontab entry

Add this entry to the crontab for the root user. Public keys will get updated at 9:30am every morning unless manually triggered. [This](https://git.xigen.co.uk/jas-dr/scripts/blob/master/bin/update-ssh-keys) will handle updating all users authorized_keys file.

30 9 * * * /root/bin/update-ssh-keys.sh
