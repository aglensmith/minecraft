## Server Maintenance


Update paperclip.jar

```
wget --content-dispositionin https://ci.destroystokyo.com/job/PaperSpigot/lastSuccessfulBuild/artifact/paperclip.jar
rm ./paperclip.jar
mv ./paperclip.jar.1 ./paperclip.jar
```

```
# the command to start the server as a daemon (run it but minimize it straight the way/send to background) you do the following:

screen -dmS minecraft java -Xms1024M -Xmx1024M -jar minecraft_server.jar nogui

# Or you can run it but with the screen session still active:

screen -S minecraft java -Xms1024M -Xmx1024M -jar minecraft_server.jar nogui

# Detatch: 
Ctrl+a+d

# Retatch:
screen -r minecraft

```
