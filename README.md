### SETUP
* W Minecraft Launcher -> Edit profile -> Use version, wybieramy "1.6.4"
* Klikamy "Play", czekamy załadowanie, wychodzimy z gry
* Ściągamy paczkę [stąd](https://drive.google.com/a/netguru.pl/file/d/0Bx7HTw5QxvkTWjYxaFRwY1pYSms/edit?usp=sharing)
* Rozpakowujemy
* Odpalamy Forge Installer:
```sh
$ chmod +x forge-1.6.4-9.11.1.965-installer.jar
$ java -jar forge-1.6.4-9.11.1.965-installer.jar
```
* Wybieramy Install Client
* Pullujemy repo do katalogu z modami:

```sh
$ mkdir "~/Library/Application Support/minecraft/mods"
$ cd "~/Library/Application Support/minecraft/mods"
$ git init
$ git remote add origin git@github.com:nekath/mods.git
$ git pull origin master
```

* W Minecraft Launcher -> Edit profile -> Use version, wybieramy 'release … forge …'
* Klikamy Play
