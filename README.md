# Luanti-Server
Projet du 27/11/25

Afin de pouvoir être mené à bien, vous allez devoir faire preuve de rigueur, d’autonomie,
et également avoir un sens aiguisé de l’organisation (si travail en binôme).
Dans un premier temps, il est conseillé de prendre connaissance du service Luanti, et en
particulier la partie serveur (configuration, structure et arborescence des fichiers, …).
Une fois fait, vous pouvez commencer à vous intéresser au projet.
Le projet:
Vous allez concevoir une solution serveur qui répond à l'ensemble des exigences ci-
dessous:
- Le serveur doit proposer plusieurs version du services (voir plus loin)
- Les informations concernant votre serveur (état de santé du serveur et des
services, dernier redémarrage du serveur et/ou des services, …), et aux différents
mondes doivent être fournies via une page web sécurisée via SSL.

#Quelques Détails 

Le serveur doit disposer d’au moins 5 mondes (world):
- monde classique: Configuration standard, sans particularité (Vanilla).
- monde créatif: Configuration standard, mais où les joueurs ont des droits
particuliers, mais spécifique à un mode de jeu créatif.
Il doivent également pouvoir activer le vol, la course, la capacité de passer au
travers des blocs. Les joueurs ne peuvent pas se blesser, et les dégâts sont
désactivés.
- monde exploration: les joueurs ont des droits très limités, en particulier en ce qui
concerne la construction (interdite).
Il doivent également pouvoir activer le mode course. Les joueurs ne peuvent pas
se blesser, et les dégâts sont désactivés.
Les droits sur le serveur sont distribués en jeu par l’administrateur. De plus, ce
dernier doit reposer sur une carte générée par IGN (voir annexe).
- monde survie: Il s’agit d’une version avec le mode VoxelLibre.
- monde perso: Vous réalisez une configuration de votre choix, différente des
précédentes

Scripting

Vous devez posséder un ensemble de script qui vous permet d’administrer le serveur et
les mondes. Libre à vous de trouver les scripts qui vous seront utiles

Cybersécurité

Vous devez mettre en place toutes configurations et/ou services qui permettent de
sécuriser le serveur.
Il est demandé, tout particulièrement, de mettre en place une sécurité concernant les
comptes des joueurs en cas d’attaques de type force brute.
