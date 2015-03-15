# config-ssh
Scripts for managing local SSH configuration

```
Usage: config-ssh { show | list | add | remove | help }
Manage local SSH configuration

Commands:
    show            Display an individual entry. Shows all information
    list [-v|-u]    Display all entries in short format 'alias : hostname'. If
                    -v option is specified, all information is displayed for
                    all entries. If -u option is specfied, entry is shown as
                    'alias : user@hostname'
    add -a ALIAS -h HOSTNAME [-u USER] Add an entry. if -u is not provided,
                    user 'root' is assumed
    remove -a ALIAS Remove entry defined by ALIAS
    help            Display this help
```
TODO: Implement remove!
