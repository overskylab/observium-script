# observium-script module

## Module
### hdarray
Modify script hdarray for use with general LSI 2960-8i with BBU (not include brands like DELL, HP, etc.) and using `MegaCli` management tool

## Preparation
prepare "Unix agent" for run script module, follow this link:

[http://www.observium.org/docs/unix_agent/] (http://www.observium.org/docs/unix_agent/)

## Installation module
Put this code into `/usr/lib/observium_agent/local/` on your agent host.

Make script is executable (+x)
```sh
chmod +x hdarray
```

## Testing
`telnet your_server 36602` from observium server
