# Minecraft Server

## Objectif

Héberger un serveur Minecraft sur Debian.

## Configuration

- OS : Debian
- Java : OpenJDK
- RAM : 8 GB

## Commandes utilisées

```bash
mkdir minecraft
cd minecraft

java -Xmx8G -Xms4G -jar server.jar nogui
```

## Ce que j'ai appris

- Gestion des processus.
- Utilisation de Java.
- Administration d'un service.

## Difficultés rencontrées

- Configuration initiale.
- Comprendre le fichier eula.txt.

## Notes personnelles

Le serveur Minecraft est mon premier véritable service hébergé sur mon Homelab.
