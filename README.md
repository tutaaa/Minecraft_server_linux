# MInecraft_server_linux
## this is minecraft server which can run in linux OS and Windows OS 
### Server description
 - server : paper server
 - version : 1.18.2
 - edition : java edition
 - author : tutaaa

## Installiation

### install java version 18
```
sudo apt install openjdk-17-jre-headless 
```
### and then install ngrok for port forwarding
```
sudo snap install ngrok
```
### add ngrok authtoken 
```
ngrok config add-authtoken XXXXXXXXXXXXXXXXXXXXXXXXX
```
## run this server
 
### Port fowarding (Asia pacific)
 ```
  ngrok tcp 25565 --region ap
 ```
### Lanch command
```
sudo java -Xms1G -Xmx3G -jar paper-1.18.2-372.jar nogui
```
