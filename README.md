# Ntripcaster binaries
GNSS ntrip broadcaster executables.

## Features
1. Support Ntrip 1.0 protocol. Support ntrip clients and servers, and dynamic source table.
2. Support Linux and Windows.
3. By default, this ntrip clients(MAX=5) and servers(MAX=3) max count online is limited. These limit can be set by config file.
4. By default, ntrip clients username is 001@whu, password is 123. The program support multiple clients username and mountpoint control, this can be set by config file.
5. By default, ntrip servers password is admin. The program support multiple servers passwords and mountpoint control, this can be set by config file.

## Source Code
The program is written in C, using libev. The source code open source, see https://github.com/lazytinker/ntripcaster
