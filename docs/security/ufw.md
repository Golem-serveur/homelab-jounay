# UFW

## Objectif

Mettre en place un firewall simple sur Debian.

## Commandes utilisées

```bash
sudo ufw enable
sudo ufw status
sudo ufw allow ssh
sudo ufw allow 25565/tcp
sudo ufw deny 23
```

## Ce que j'ai appris

- Fonctionnement d'un firewall.
- Ouverture et fermeture des ports.
- Sécurisation des services.

## Difficultés rencontrées

- Comprendre les ports.
- Éviter de bloquer SSH.

## Ressources

- https://wiki.debian.org/UncomplicatedFirewall

## Notes personnelles

UFW est un excellent premier firewall avant OPNsense.
