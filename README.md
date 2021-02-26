# Book_Projet_Final

Ce projet consiste à comprendre le système de gestion d'emprunt des livres dans une librairie.

Le code est au format .ipynb et il retourne un fichier csv composé de la table Borrow qui précise si la durée d'emprunt des livres est supérieur à 3 mois.

Ce fichier crée et utilise ces tables : 
- Author : représente une table d'auteurs. Chaque ligne contient le nom et l'identifiant d'un auteur ;
- Book : représente une table de livres. Chaque ligne est un livre décrit par son identifiant, son titre et sa catégorie ;
- Student : représente une table d'étudiants. Chaque ligne est un étudiant décrit par son identifiant, son nom et son département ;
- Write : représente l'association entre les auteurs et les livres. Une ligne de cette table signifie que l'auteur a écrit le livre bid ;
- Borrow : représente les informations de prêt de livre. Une ligne de cette table signifie que l'étudiant a emprunté le livre bid, à la date checkout-time et l'a retourné à la date return-time.

