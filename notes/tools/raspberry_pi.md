# Raspberry PI 3
## OS Download
* https://www.raspberrypi.com/software/operating-systems/

## Image tool 
* https://www.balena.io/etcher/

## SD Card Todos
### SSH Enable
Go to boot part, add a empty file `ssh`.

### Add User
Info by `bullseye` image, see: https://www.raspberrypi.com/news/raspberry-pi-bullseye-update-april-2022/

Go to boot part, add a file `userconf`, and insert a line with `username:passwordhash`.

A password hash can create with shell command:

`echo "password" | openssl passwd -6 -stdin`

For example:

`pi:$6$38HiUnLhwlE1DRdL$MHHb6/OsyAlZNqmW7igj333g/CRwG/g5nls7ylTEqZZg9rOIM/cUvE962.5x6M0ONMz/r6OlBy/G6f4v8zrH51`

## Raspberry PI Projects
* https://raspap.com/
