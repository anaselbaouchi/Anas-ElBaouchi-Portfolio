# Anas-ElBaouchi-Portfolio

Projet 1 : Système de Présence Basé sur RFID et Raspberry Pi
* Contexte et Objectifs
Ce projet a été développé pour automatiser la gestion de présence des étudiants ou employés à l'aide de la technologie RFID. En utilisant un Raspberry Pi 3 comme contrôleur principal, l’objectif était de créer une solution fiable et sécurisée permettant :

L'authentification via cartes RFID.
La sauvegarde et analyse des données.
L'accès hors ligne avec synchronisation ultérieure.

* Technologies et Matériel Utilisés
- Matériel :
Raspberry Pi 3
Lecteur RFID RC522
LEDs pour indication visuelle
Buzzer pour signalisation
Breadboard et résistances

- Logiciel :
Langage : Python
Bibliothèques : RPi.GPIO, MFRC522, sqlite3
Base de données : SQLite pour stocker les présences
Interface utilisateur : Affichage des statistiques et gestion des utilisateurs

- Fonctionnalités Clés
Authentification sécurisée : Accès réservé aux professeurs via un login.
Mise à jour des cartes : Gestion et réémission en cas de perte.
Backup des données : Sauvegarde automatique des présences.
Mode hors ligne : Stockage local des scans en cas de coupure réseau.
Statistiques de fréquentation : Analyse des tendances de présence.


----------------

Projet 2 : Développement d’une Interface Graphique en C++ 
* Contexte et Objectifs
Ce projet consiste à créer une interface utilisateur (GUI) permettant d’obtenir le numéro atomique d’un élément chimique en entrant son symbole. Il a été développé avec C++ et la bibliothèque wxWidgets pour une interface fluide et interactive.

- Technologies et Outils
Langage : C++
Bibliothèque : wxWidgets (GUI)
IDE : Visual Studio

- Fonctionnalités Clés
 Interface intuitive : Champ de saisie et bouton de validation.
 Base de données intégrée : Vérification des symboles chimiques (H, He, Li, etc.).
 Affichage dynamique : MessageBox indiquant le numéro atomique.
 Gestion des erreurs : Message d’alerte si le symbole est invalide.

------------------

Projet 3 : Gestion synchronisée d’une base de données sur plusieurs machines (En cours de réalisation)
* Contexte et Objectifs
L’objectif de ce projet est de permettre la manipulation et la synchronisation en temps réel d’une base de données entre deux machines ou systèmes d’exploitation différents. Toute modification effectuée sur l’une des machines (ajout, suppression, mise à jour) doit être immédiatement répercutée sur l’autre machine.

- Technologies (en cours de sélection)
Ce projet explorera différentes technologies pour assurer la cohérence et la performance de la synchronisation, notamment :
Un SGBD adapté 
Un mécanisme de synchronisation efficace
Un langage backend pour gérer la communication et la gestion des données 

- Fonctionnalités prévues
 Synchronisation en temps réel entre les deux machines.
Gestion des conflits en cas de modification simultanée.
Stockage sécurisé et cohérent des données.
Interface pour visualiser et gérer les modifications.

 Statut actuel : En phase de conception et de choix technologique.
