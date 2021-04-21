# M4-BACKUP SYSTEM

Sistema de Backup Online para la M4 Board Amstrad

## Requisitos
### Software

```shell
- libcrypto++ libpcrecpp0v5 libc-ares-dev zlib1g-dev libuv1 libssl-dev libsodium-dev readline-common sqlite3 curl autoconf libtool g++ libcrypto++-dev libz-dev libsqlite3-dev libssl-dev libcurl4-gnutls-dev libreadline-dev libpcre++-dev libsodium-dev libc-ares-dev libfreeimage-dev libavcodec-dev libavutil-dev libavformat-dev libswscale-dev libmediainfo-dev libzen-dev
- build-essential
- git
- telnet
- telnetd
- curl
- boxes
- figlet
- dialog
- whiptail
- erlang-getopt
- apache2
- jq
- shc
```

### Configuraciones

- No pedit password de sudo
- Añadir a .bashrc variable PATH=$PATH:/home/amstrad/.m4bs/bin
- Añadir link simbolico de ln -s /usr/lib/cgi-bin /home/amstrad/.m4bs/cgi
- Configurar texto bienvenida de ssh y telned

### Activaciones
- a2enmod cgi


