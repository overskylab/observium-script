# observium-script module
## Preparation
prepare "Unix agent" for run script module, follow this url:

[http://www.observium.org/docs/unix_agent/] (http://www.observium.org/docs/unix_agent/)

## Installation module
Put this code into /usr/lib/observium_agent/local/ on your agent host.

Make script is executable (+x)
```sh
chmod +x hdarray
```

## Testing
```sh
telnet your_server 36602
```
from observium server
