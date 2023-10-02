# SSH

## Installation (One time)
### Developer SSH Keys
```sh
curl -o ~/.ssh/authorized_keys "https://raw.githubusercontent.com/XigenIO/Developer-SSH-Keys/master/authorized_keys"
```
### SysOps SSH Keys
```sh
curl -o ~/.ssh/authorized_keys "https://raw.githubusercontent.com/XigenIO/Developer-SSH-Keys/master/authorized_keys_sys"
```

## Installation (Crontab - current user)
### Developer SSH Keys
```sh
crontab -e
```
```sh
0 0 * * * curl -o ~/.ssh/authorized_keys "https://raw.githubusercontent.com/XigenIO/Developer-SSH-Keys/master/authorized_keys"
```

### SysOps SSH Keys
```sh
crontab -e
```
```sh
0 0 * * * curl -o ~/.ssh/authorized_keys "https://raw.githubusercontent.com/XigenIO/Developer-SSH-Keys/master/authorized_keys_sys"
```

## Adding new keys
Open up a pull new pull request with a modification to the authorized_keys file.
