## Healthchecker.

A tiny tool that checks the given domain is down or not written in Go.

```bash
go run . --domain <domain name>
```

## Usage

```
NAME:
   Healthchecker - A tiny tool that checks the given domain is down.

USAGE:
   healthchecker [global options] command [command options] [arguments...]

COMMANDS:
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --domain value, -d value  Domain name to check.
   --port value, -p value    Port number to check.
   --help, -h                show help (default: false)

```