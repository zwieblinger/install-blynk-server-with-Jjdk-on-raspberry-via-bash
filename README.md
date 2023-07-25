# Install Blynk Server with JDK on Raspberry via Bash

This script does the following:
  * Update and Upgrade
  * Installs OpenJDK 8
  * Downloads and initializes the Blynk Server
  * Installs the server as a systemd service if you so choose


3 Steps to Install:

Step 1 - Clone this repo

```shell
git clone https://github.com/zwieblinger/install-blynk-server-with-Jjdk-on-raspberry-via-bash.git
```

Step 2 - Run the installer script
```shell
cd ./installblynkpi
```
```shell
sudo chmod +x ./install.sh
```
```shell
sudo ./install.sh
```

Step 3 - Answer "Yes" if you would like it to start on boot


That´s it ! Have fun !


## Uninstall
1) Make the uninstall script executable
```shell
chmod +x ./uninstall.sh
```
2) Run the uninstaller and follow the prompt
