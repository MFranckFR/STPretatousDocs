# STPretatousDocs

# PretATous - Fonctionnalités

## Description

Le projet **PrêtATous** propose via une Web Application de prêter ou d’emprunter des livres, jeux de société, outils (liste de produits non exhaustive).

On retrouve le principe de la « bibliothèque » avec la possibilité de réserver, emprunter et restituer un produit.

L’équipe est constituée de Franck et Jean-Baptiste

## Choix des Technos

BackEnd : node Express
FrondEnd: Angular / Javascript / Bootstrap / Material UI
BDD : MongoDB

## Lien du Trello avec les user Stories

- [Les Fonctionnalités](https://hackmd.io/w8Vzsr7nSZOtQgbI0wUybg?view)
- [Les schémas : modèles, navigation, diagramme d'état](https://hackmd.io/pBscB-ART1OPuhgdrnWptg?view)
- [Les Stories](https://hackmd.io/Hco8h-fyT-GsMnnzd2D2sw?view)
- [Spécifications partielles](https://hackmd.io/7TjO7jEIRFCHFKvluZdQIw?view)
- [Lien vers le Trello](https://trello.com/b/Fw6c5l6Y/pr%C3%AAtatous)

- [Annexes](https://hackmd.io/ct5EnR79RbCqxN-Aa0C9dw?view)




## Coeur de l'application (standalone)

- Gérer les utilisateurs
    - Ajouter un nouvel utilisateur
    - Modifier un utilisateur
    - Supprimer un utilisateur


- Gérer une annonce produit
    - Créer une annonce produit
    - Modifier une annonce produit
    - Supprimer une annonce produit
    - Publier une annonce produit

- Prêter un produit
    - Réserver un produit
    - Annuler la réservation
    - Remise (en main propre) un produit
    - Récupérer (en main propre) un produit

- Lister les produits
    - Lister les produits non-empruntés
    - Lister les produits prétés
    - Lister les produits réservés


## Etendre le partage à d'autres utilisateurs

- Gestion d'un compte associé à un utilisateur
    - Créer un compte
    - Modifier le compte
    - Supprimer le compte

- Validation d'une demande de réservation d'un produit (côté prêteur)
    - Accepter la demande de réservation
    - Refuser la demande de réservation
    - Annuler une demande de réservation (côté emprunteur)


- Des alertes
    - Etre alerté du retour d'un produit
    - Etre alerté du seuil de dépassement d'un prêt côté prêteur
    - Etre alerté du seuil de dépassement d'un emprunt côté emprunteur
    
 - Echanger des messages entre utilisateurs
     - messages associés à une annonce produit.
     - Donner son avis sur une annonce produit
     - Donner son avis sur un utilisateur

- Valider une annonce produit (gestionnaire application)
    - Visualiser une annonce produit avant publication
    - Valider/refuser une annonce produit
