### Card install
1. Flash the image
2. Put the ssh key inside /root/.ssh
3. Put into device
4. Wait for restart. Hard restart.

### First boot
1. Login as root
2. Set root pasword
2. Crate user 
  ```
  useradd -m  -s /bin/bash ligasm
  passwd ligasm
  ```
3. Set password
4. Move the ssh key form root
5. Update distor. 
  ``` 
  apt-get update && apt-get upgrade && apt-get dist-upgrade && apt-get autoremove && apt-get clean && apt-get update
  ```
6. Restart 
7. Log out & login as ligasm

### Software install
1. Install 
  ```
  apt-get install mariadb-client mariadb-server apache2 transmission-cli transmission-daemon transmission-common php php5 php-pear php5-mysql php5-mcrypt zip unzip ca-certificates git

  ```

 

