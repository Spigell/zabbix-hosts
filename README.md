# SYNOPSIS

Extract IP and hostnames from zabbix server

# INSTALL

    $ sparrow plg install zabbix-hosts

# USAGE

## Manually

    $ sparrow plg run zabbix-hosts --param user=foo --param password=bar --param host=127.0.0.1

# Parameters

## user

A user to login. No default value. Obligatory.

## password

A password. Obligatory.

## host

IP or dns name of zabbix server. Obligatory.

## output 

Default is `stdout`. If any other specified output will be in file.

