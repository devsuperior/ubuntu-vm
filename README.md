# Ubuntu 20.04 LTS no VirtualBox
###### DevSuperior - sua carreira dev com fundamento de ensino superior

[![Image](https://s3-sa-east-1.amazonaws.com/educandoweb.com.br/img/devsuperior/bt-youtube.png "DevSuperior no Youtube")](https://www.youtube.com/channel/UC3twHmWQwtqEO7u-gB_2f7g) [![Image](https://s3-sa-east-1.amazonaws.com/educandoweb.com.br/img/devsuperior/bt-facebook.png "DevSuperior no Facebook")](https://www.youtube.com/channel/UC3twHmWQwtqEO7u-gB_2f7g) [![Image](https://s3-sa-east-1.amazonaws.com/educandoweb.com.br/img/devsuperior/bt-instagram.png "DevSuperior no Instagram")](https://www.youtube.com/channel/UC3twHmWQwtqEO7u-gB_2f7g)

Assista o vídeo:

[![Image](https://img.youtube.com/vi/TIZ1PNH0128/mqdefault.jpg "Vídeo no Youtube")](https://youtu.be/TIZ1PNH0128)

## Sumário
- [O que você vai aprender](#O-que-você-vai-aprender)
- [Pré-requisitos](#pré-requisitos)
- [Códigos utilizados](#Códigos-utilizados)

## O que você vai aprender
- Instalar VirtualBox
- Criar uma VM Linux Ubuntu
- Instalar o Ubuntu na VM
- Configurar a resolução de tela full HD

## Pré-requisitos

- Computador Windows ou Mac com 8GB de memória RAM

## Códigos utilizados

```
xrandr --newmode "1920x1080"  173.00  1920 2048 2248 2576  1080 1083 1088 1120 -hsync +vsync
xrandr --addmode Virtual1 1920x1080
xrandr --output Virtual1 --mode 1920x1080
```

```
[Desktop Entry]
Type=Application
Exec=/usr/local/sbin/screen.sh
Hidden=false
NoDisplay=false
Name=Screen Full HD
X-GNOME-Autostart-enabled=true
```
