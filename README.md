# Projet Serveur/Client TCP/UDP

## Description

Ce projet implémente un système de communication client-serveur en **TCP** et **UDP**, permettant l'échange de messages entre un client et un serveur. Deux modes d'exécution sont disponibles :

- **Exécution standard** : Lancer un client et un serveur séparément.
- **Utilisation de ****`main.c`** : Interface facilitant l'utilisation des clients avec une meilleure présentation.

## Contenu du projet

- **main.c** : Interface permettant de choisir un client TCP ou UDP et d'envoyer des messages plus facilement.
- **client\_tcp.c** : Implémentation d'un client utilisant le protocole TCP.
- **client\_udp.c** : Implémentation d'un client utilisant le protocole UDP.
- **serveur\_tcp.c** : Serveur TCP recevant les messages des clients TCP.
- **serveur\_udp.c** : Serveur UDP recevant les messages des clients UDP.

## Installation

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/Ismaelwn/RESEAU_CLIENT_SERVER.git
   ```
2. **Compiler les fichiers** :
   ```bash
   gcc -o serveur_tcp serveur_tcp.c
   gcc -o serveur_udp serveur_udp.c
   gcc -o client_tcp client_tcp.c
   gcc -o client_udp client_udp.c
   gcc -o main main.c
   ```

## Utilisation

### Méthode standard

1. **Lancer un serveur** :
   - Pour TCP :
     ```bash
     ./serveur_tcp
     ```
   - Pour UDP :
     ```bash
     ./serveur_udp
     ```
2. **Lancer un client** :
   - Pour TCP :
     ```bash
     ./client_tcp
     ```
   - Pour UDP :
     ```bash
     ./client_udp
     ```
3. **Échanger des messages** entre le client et le serveur.

### Utilisation de `main.c`

1. **Lancer le serveur souhaité** (TCP ou UDP).
2. **Exécuter ****`main.c`** :
   ```bash
   ./main
   ```
3. **Choisir le type de client** et envoyer des messages en boucle.
4. Pour une meilleure expérience, utilisez un terminal en **plein écran (1366 × 768)**.

## Fonctionnalités supplémentaires

- Vérification des paramètres saisis par l'utilisateur.
- Interface améliorée avec `main.c` pour une meilleure lisibilité.
- Gestion des erreurs lors des connexions client-serveur.

## Contributions

Les contributions sont les bienvenues !

1. **Forker le dépôt**.
2. **Créer une branche** (`git checkout -b feature/NouvelleFonctionnalite`).
3. **Commiter vos modifications** (`git commit -m "Ajout d'une nouvelle fonctionnalité"`).
4. **Pousser votre branche** (`git push origin feature/NouvelleFonctionnalite`).
5. **Ouvrir une Pull Request**.

##
