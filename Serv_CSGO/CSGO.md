# Compte rendu projet

Description du projet : création d'un serveur cs:go

## Date de la  séance : 23/11/2022

### Fait pendant la séance : avancement du projet personnel sur la création d'un serveur cs:go

- Mise en place du serveur
- installation de steamcmd
- mise en accord sur le choix de la map
- fichier .BAT pour lancer le serveur
- fichier Update.BAT pour mettre a jour le serveur lors de maj
- en attente d'un accès a la box pour a cause des ports

### A faire pendant la séance prochaine : avancement du projet personnel sur la création d'un serveur cs:go

---

### Date de la  séance : 07/12/2022

### Fait pedant la séance : avancement du projet personnel sur la création d'un serveur cs:go

- ouverture des ports sur la box
- installation de différents asset comme des map
- modification des paramètres pour rendre le serveur plus agréable

### A faire pendant la séance prochaine : activer les mods

---

### Date de la  séance : 04/01/2023

### Fait pendant la séance : avancement du projet personnel sur la création d'un serveur cs:go

- installation des mods
- mise en place des règles du serveur
- mise en place du vac

### A faire pendant la séance prochaine : faire le motd

---

### Date de la  séance : 18/01/2023

### Fait pendant la séance : avancement du projet personnel sur la création d'un serveur cs:go

- creation du motd
- mise en place du motd
- fichier de mise a jour en .bat

---
## Compte-rendu actuel de notre projet par rapport au objectif demandé

### 🎯 Objectifs

### - Mettre en place un serveur CS:GO avec les outils Steam Valve 
    • A l'aide du SteamCMD notre serveur a bien été installé

    • j'ai créer et configurer un fichier Serveur.BAT permettant d'exécuté notre serveur et de le lancé, à l'intérieur ce trouve également certain fichier de conf qu'il doit exécuté au démarrage, tel la map_list et la map_cycle et la map lancé au démarrage, également si trouvé une clé steam.

    • J'ai également créer un fichier Update.bat permettant que lorsque le jeu une nouvelle mise a jour d'exécuté ce fichier qui vas automatiquement mettre a jour le serveur.

    • Pour l'administration du serveur ce trouve le fichier server.cfg il permet de gérer tel que son nom, mot de passe, système des download du serv, anti-chaet, tout les paramètres de base etc..

 • Ci-joint les fichiers que j'ai cité : [Serveur.bat](./fichier_utile/Serveur.bat), [Update.bat](./fichier_utile/Update.bat) et [server.cfg](./fichier_utile/server.cfg)

### - Mettre en place un mode de jeu personnalisé (GunGame ou autre)
    • J'ai un mis en place un système de GunGame assez personnalisé, il contient système de niveau que l'on augmente a la suite d'élimination permettant le changement de l'arme, fournit avec un panel expliquant le jeu et donner accès à des commandes pour voir la liste des armes, le leaderboard, notre niveau actuel etc ..

### - Ajouter un MOTD personnalisé
    • L'ajout du motd est assez sophistiqué car nous l'avons créer au travers de notre GunGame, c'est à dire qu'il fait partie du texte inclut par le GunGmae a udébut du jeu.

### - Gérer les règles de démarrages (nombre de manche, argent, loadout…)
    • De nombreux fichier .cfg me permettent de modifier les règles et le fonctionnement du jeu néanmoins le principal est gamemode_casual.cfg, celui ci peut modifié la quasi totalité des réglages mais également les réglages des bots, et un système rendant la difficulté des bots à notre niveau en jeu.
 • Ci-dessous le fichier : [gamemode_casual](./fichier_utile/gamemode_casual.cfg)

### - Ajouter des assets personnalisés
    • J'ai réalisé l'ajout d'asset tel que de map custom, de skin ou encore de l'interface visuel

### - Mettre en place un système de sauvegarde régulière (cron ou autre)
    • Copie du dossier du serveur dans un autre dossier pour pouvoir le save dans le cas de problème.   
---
## Bonus
### - Activer le VAC Anti-cheat
    • L'anti-cheat VAC est activé