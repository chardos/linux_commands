## General

#### Read a file
- `cat <filename>`

## Permissions

#### See permissions on files and directories
- `ls -l`

#### Changing Permissions
There are three types of users, (u)sers, (g)roups, (o)thers.
- `chmod u=rwx,g=rx,o=r myfile`
- `chmod -R 777 myfile`

## Crontab

#### Crontab - edit a users crontab
- `sudo crontab -u <username> -e`

#### Crontab - see the formatting
- `sudo vim /etc/crontab`

## Users

#### Change to super user
- `sudo sh`
- `su`

#### Change back to user
- `su <username>`
