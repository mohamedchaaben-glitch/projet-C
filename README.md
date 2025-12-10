Gestion des Réservations de Salles — Projet en C :

Ce projet est une application en langage C permettant de gérer des salles, leurs réservations, les clients ainsi que plusieurs fonctionnalités avancées : disponibilité, statistiques, annulation, facturation, recherche par équipement, etc.

--Fonctionnalités principales
-Gestion des salles

-Ajouter une nouvelle salle

-Capacités, tarif horaire, équipements

-Sauvegarde automatique dans salles.dat

--Gestion des réservations :

-Créer une réservation (client, salle, date, horaire, nombre de personnes)

-Validation de la date

-Vérification de disponibilité

-Calcul automatique du montant

-Génération d’une facture .txt

-Sauvegarde dans reservations.dat

--Gestion :

-Liste complète des réservations

-Annulation d’une réservation

-Modification du nombre de personnes

-Recherche par équipement

--Statistiques :

-Chiffre d’affaires par salle

-Nombre de réservations par mois

-Classement des salles les plus populaires

--LES NOTIONS DE COURS UTILISES :

1) Les structures (struct) :

C’est un type personnalisé qui regroupe plusieurs informations dans une seule variable.

 2) Les tableaux de structures :

Pour stocker plusieurs salles ou réservations.

3) Les fichiers :

le programme lit et écrit des données dans des fichiers .dat.

4) Les fonctions

Le code utilise beaucoup de fonctions pour organiser les tâches.

5) Les chaînes de caractères (char[]) :

Utilisées pour stocker les textes (nom, date, équipements…).

6) Les conditions (if,else) :

Très utilisées pour vérifier :

que la date est valide

que la salle existe

qu’il n’y a pas de conflit de réservation

que la capacité est suffisante


7)Les boucles (for, while) :

Elles permettent :

d’afficher toutes les salles

de rechercher une salle

d’afficher toutes les réservations

de supprimer une réservation (décalage du tableau)


8) Les menus :

Le programme utilise un menu principal pour guider l’utilisateur.

9) La gestion des erreurs :

Messages affichés si :

Salle introuvable

Capacité insuffisante

Date invalide

Réservation déjà existante

Fichier introuvable



