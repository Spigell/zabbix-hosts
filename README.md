# SYNOPSIS

Extract IP and hostname from zabbix server

# INSTALL

    $ sparrow plg install zabbix-host

# USAGE

## Manually

    $ sparrow plg run zabbix-host --param user=foo --param password=bar --param host=127.0.0.1

# Parameters

## user

A user to login. No default value. Obligatory.

## password

A password. Obligatory.

## host

ip or dns name of zabbix server. Obligatory.

## output 

Default is `stdout`. If any other specified output will be in file.

