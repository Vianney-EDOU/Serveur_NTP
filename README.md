# Serveur_NTP
Mettre en place un serveur NTP (Network Time Protocol) dans un réseau local est une tâche essentielle pour assurer la synchronisation précise des horloges de tous les dispositifs sur le réseau.

I. Pré-requis :

1/ Un serveur avec une distribution Linux installée (Debian, Ubuntu, CentOS, etc.).

2/ Accès administrateur au serveur.

3/ Connexion au réseau local où le serveur NTP sera déployé.



II. Installation du serveur 

Téléchargez et installez la dernière version du serveur Ubuntu ici: https://releases.ubuntu.com/24.04/ubuntu-24.04-live-server-amd64.iso


III. Installer le serveur NTP

connectez-vous à votre serveur et executez cette commande dans le terminal: 

- Mettre à jour la liste des paquets disponibles sur un système basé sur Debian ou Ubuntu

sudo sudo apt update


- Mettre à jour les paquets installés avec la commande

sudo apt upgrade


sudo apt-get install ntp
