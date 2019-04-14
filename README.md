Bonjour à tous,

je vous partage un serveur mini-jeux pour un événement hiver/noël réalisé par mes soins avec un ami.

/!\ Si vous êtes nul en BungeeCord (Proxy qui permet de lié les serveurs sans changer d'ip manuellement, très utile pour les serveurs mini-jeux), ou que vous cherchez à faire votre propre serveur mini-jeux, ou pour prendre quelques plugins/maps ce partage est fait pour vous. /!\

I. Composition du partage

L'ensemble du partage est déjà configuré (le serveur à été testé par 16 personnes simultanément sur un serveur dédié), le partage est composé de:

- BungeeCord (ViaVersion, Party, BungeeEssentials)
- Bedwars 4 équipes de 4 joueurs et 8 équipes de 2 joueurs (+ émeraude et diamant avec hologrammes avec map réalisé par Azengold)
- BuildBattle (à reconfigurer pour les votes des thèmes)
- Sheepwars (map réalisé par Azengold)
- Lobby (map inspiré de Hypixel modifié par nos soins, avec UltraComestic, Jump, AnimatedFrames, CratesPlus, HubBasics...)
- TheTowers (map de base avec quelques modifications esthétiques)

La plupart des plugins mini-jeux sont automatiques comme le Bedwars lancé automatiquement quand le minimum de joueurs est atteins. Si vous ne savez pas utiliser les plugins cités au dessus merci de vous renseignez sur les partages des plugins (disponible sur spigotmc par exemple).

II. Configuration

Le serveur est configuré en localhost (à utiliser avec hamachi). Pour le configurer sur un serveur dédié/vps ou hamachi vous devez changer les lignes dans proxy/config.yml:

forced_hosts:
    localhost: lobby
par
forced_hosts:
    IP DE VOTRE MACHINE/VPS OU IPv4 Hamachi: lobby

et 

host: localhost:25565
par
host: IP DE VOTRE MACHINE/VPS OU IPv4 Hamachi:25565

Pour Hamachi: Lancer tout les run.bat sur votre ordinateur

Pour les dédiés ou vps: supprimer le run.bat et ajouter à la place un nouveau fichier run.sh
Pour le run.sh Bungeecord
 #!/bin/sh java -Xms512M -Xmx512M -jar BungeeCord.jar 
Pour le run.sh Spigot
 java -Xms512M -Xmx1024M -jar -XX:ParallelGCThreads=1 spigot.jar 

Mettez vous administrateur dans proxy/config.yml au niveau de groups puis pour se déplacer entre les serveurs (car le menu au lobby n'est pas complètement finis) taper la commande /server <nom du serv>

Pour utiliser les différentes fonctionnalités mettez-vous opérateurs, aller dans chaque console du serveur et faite "op votrepseudo"


Faites en bon usage, vous pouvez également modifier les textes, et map pour faire un event Paques par exemple ou autres. Libre à votre créativité et envies.

Téléchargement: (Cliquez sur "Clone or download" puis "Download ZIP")

Screenshots:
https://image.noelshack.com/fichiers/2019/15/7/1555259936-unknown-5.png
https://image.noelshack.com/fichiers/2019/15/7/1555259950-unknown-6.png
https://image.noelshack.com/fichiers/2019/15/7/1555259959-unknown-7.png
https://image.noelshack.com/fichiers/2019/15/7/1555259968-unknown-8.png
https://image.noelshack.com/fichiers/2019/15/7/1555259971-unknown.png
https://image.noelshack.com/fichiers/2019/15/7/1555259924-unknown-4.png
https://image.noelshack.com/fichiers/2019/15/7/1555259908-unknown-1.png
https://image.noelshack.com/fichiers/2019/15/7/1555259916-unknown-2.png
https://image.noelshack.com/fichiers/2019/15/7/1555259921-unknown-3.png
