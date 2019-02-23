# Bibliothèque

## Les besoins
La bibliothèque "La Manu" vient d'ouvrir et elle ne dispose pas de logiciel pour suivre ses livres.  
Vous êtes donc en charge de créer une base de données permettant de faciliter cette gestion.  

## Les contraintes
La bibliothèque souhaiterait pouvoir enregistrer ses clients, enregistrer tous ses livres et surtout, suivre ses livres empruntés.  

Les **clients** sont définis par leur **nom** et **prénom**, leur **date de naissance**, leur **mail**, leur **genre** de livre qu'ils préfèrent.  
Les **livres** sont définis par leur **titre**, leur **genre**, le **nom** et **prénom** de leur auteur.  
Le **registre** d'emprunts contient le **titre** du livre, la **date d'emprunt** et la **date de retour**, le **nom** et **prénom** du client.    

## Les choses à savoir
La bibliothèque "La Manu" ne possède que **4 genres de livre** :  
  * Horreur
  * Science Fiction
  * Roman
  * Jeunesse

## Les pré-requis de votre base de données
La bibliothèque "La Manu" possède **70 livres** et **25 clients**.  
Elle possède un registre de **40 lignes** avec **14 livres** qui ne sont pas encore rendus.  

Dans ce registre, il faut également retrouver des livres populaires (Empruntés plusieurs fois).

## Fonctionnalités
1. Il faudra pouvoir afficher les lignes du registre (*titre, nom et prénom du client, date d'emprunt et de retour du livre*).  
2. Il faudra pouvoir lister tous les livres (*titre, genre, nom et prénom de l'auteur, disponibilité*).  
3. Il faudra pouvoir afficher le nombre total de livres par genre (*nom du genre, total de livres correspondants*).  
