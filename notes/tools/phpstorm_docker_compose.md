# Problem
The new docker version includes docker-compose as a plugin. As a result, the call is now "docker compose". 
This creates a problem in PHPStorm, which only knows the "docker-compose" command.

# Fix
```shell
sudo nano /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

Add Content:
```sh
#!/bin/sh

docker compose $@
```
