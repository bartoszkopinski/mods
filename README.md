### SETUP
* Ściągamy paczkę [stąd](https://docs.google.com/a/netguru.pl/uc?authuser=1&id=0Bx7HTw5QxvkTWjYxaFRwY1pYSms&export=download)
* Rozpakowujemy
* Odpalamy Forge Installer
```sh
$ chmod +x forge-1.6.4-9.11.1.965-installer.jar
$ ./forge-1.6.4-9.11.1.965-installer.jar
```
* Wybieramy Install Client
* Pullujemy repo do katalogu z modami

```sh
$ cd ~/Library/Application Support/minecraft/mods
$ git init
$ git remote add origin git@github.com:nekath/mods.git
$ git pull origin master
```

* W Minecraft Launcher -> Edit profile -> Use version, wybieramy 'release … forge …'
* Klikamy Play
