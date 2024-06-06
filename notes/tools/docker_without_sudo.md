1. Add the docker group:
  sudo groupadd docker

2. Add the connected user “$USER” to the docker group
  sudo gpasswd -a $USER docker
   
3. Either do a newgrp docker or log out/in to activate the changes to groups
  newgrp docker

4. Reboot
