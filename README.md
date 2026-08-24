# FCSC 2025 Baby XDP

Mais où sont passés mes paquets réseau ?

Dans cette épreuve nous vous proposons de jouer avec XDP.

Un attaquant a mis en place un canal de communication discret entre une machine infectée et le réseau. Saurez-vous retrouver le contenu des paquets reçus sur l’interface réseau ? tcpdump ne semble pas fonctionner…

**Remarques :**

- Afin de disposer d’un `Ctrl-c` fonctionnel, vous pourrez utiliser `stty -cooked -echo` sur votre terminal après avoir mis en tâche de fond votre connexion au challenge faite avec `nc`.
- Pour reproduire l’épreuve localement :  Décompressez l’archive avec `tar xf babyxdp.tar.xz`. Lancez le conteneur Docker avec `docker compose up --build`. Connectez-vous à l’épreuve locale avec `nc localhost 4000`.
- Pour vous connecter à la machine, utilisez le mot de passe “user”

Auteur : gte

Origine : [Baby XDP](https://hackropole.fr/fr/challenges/misc/fcsc2025-misc-baby-xdp/)


## Challenge
[files/babyxdp.tar.xz](files/babyxdp.tar.xz)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2025-misc-baby-xdp.git

> cd fcsc2025-misc-baby-xdp

> docker compose up

-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/misc/fcsc2025-misc-baby-xdp/
