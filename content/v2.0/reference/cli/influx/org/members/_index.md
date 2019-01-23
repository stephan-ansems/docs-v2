---
title: influx org members - Organization membership management commands
description: The 'influx org members' command and its subcommands manage organization members in InfluxDB.
menu:
  v2_0_ref:
    name: influx org members
    parent: influx org
    weight: 1
---

The `influx org members` command and its subcommands manage organization members in InfluxDB.

## Usage
```
influx org members [flags]
influx org members [command]
```

## Subcommands
| Subcommand | Description                |
|:---------- |:-----------                |
| add        | Add organization member    |
| list       | List organization members  |
| remove     | Remove organization member |

## Flags
| Flag           | Description        |
|:----           |:-----------        |
| `-h`, `--help` | Help for `members` |

## Global flags
| Global flag     | Description                                                | Input type |
|:-----------     |:-----------                                                |:----------:|
| `--host`        | HTTP address of InfluxDB (default `http://localhost:9999`) | string     |
| `--local`       | Run commands locally against the filesystem                |            |
| `-t`, `--token` | API token to be used throughout client calls               | string     |