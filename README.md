# TP Client-Serveur Java (ORB)

## Environnement
- OS : Windows
- Java : JDK 8+
- IDE : IntelliJ IDEA
- Python : 3.10 (via Anaconda)
- ORB : omniORB

## Installation Python / ORB (Windows)

1. Télécharger et installer [Anaconda3](https://www.anaconda.com/products/distribution)  
2. Ouvrir **Anaconda Prompt** en tant qu’administrateur  
3. Créer un nouvel environnement Python 3.10 :

conda create -n corba_env python=3.10 (terminal anaconda)

4. Activer l’environnement :

conda activate corba_env (terminal anaconda)


Installer omniORB :

pip install omniorb (terminal anaconda)

Structure

server/ : code du serveur

client/ : code du client

lib/ : bibliothèques nécessaires (ORB)

Exécution
1. Lancer le serveur

Ouvrir le projet serveur dans IntelliJ

Lancer la classe ServerMain

2. Lancer le client

Ouvrir le projet client

Lancer la classe ClientMain

NB : Le serveur doit être lancé avant le client.

Réseau

Adresse : localhost

Port : 1050
