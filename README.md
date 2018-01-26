# detectify-cli 1.0

### Prerequisites

```
curl
printf
jq
```

### Installation

Get your team API-key from [Detectify Team Settings](https://detectify.com/dashboard/team).

```
$ export DETECTIFY_API_KEY="xyz"
$ ln -s detectify /usr/local/bin/detectify

$ detectify help
```

### Help

```
detectify-cli v1.0

help                           this list of help
version                        show version of detectify-cli

[--raw]                        show raw JSON response

domains [--status=*]           list all domains, statuses: verified/unverified
profiles                       list all profiles
profiles <domain>              list profiles for the domain
start <profile>                start a scan on the profile
stop <profile>                 stop a scan on the profile
status <profile>               status of the current scan
```