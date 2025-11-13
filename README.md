# TP JDBC 
## Exercice1:Suivi des Scripts des Développeurs
### Objectifs
Maîtriser la connexion JDBC entre Java et MySQL.
Manipuler une table SQL depuis Java avec Statement et PreparedStatement.
Réaliser des requêtes SQL de sélection, d’agrégation et de tri.

 ### Contexte

Chaque développeur produit chaque jour un certain nombre de scripts.
Ce programme Java permet de :

enregistrer ces données dans une base MySQL,
puis afficher différentes statistiques :
   le maximum de scripts par jour,
   le classement des développeurs,
   le total hebdomadaire,
   et le total par développeur donné.
<img width="1873" height="753" alt="image" src="https://github.com/user-attachments/assets/22c4746c-b098-484e-97eb-0bfd9fbe43dd" />

<img width="834" height="425" alt="image" src="https://github.com/user-attachments/assets/2225919c-ddba-4924-9f98-318e63333e13" />
<img width="1897" height="793" alt="image" src="https://github.com/user-attachments/assets/eee061f0-42c0-4e47-8e48-6ad7c4b9a6c8" />

## Exercice2-Gestion des Machines et Employés :
### Objectifs pédagogiques
Comprendre l’architecture en couches :
DAO ↔ Service ↔ Présentation

Créer un Singleton JDBC pour la connexion à MySQL.

Manipuler des entités Java liées par une relation Employé–Machine.

Implémenter une interface générique DAO pour les opérations CRUD.

Sécuriser les requêtes SQL avec PreparedStatement et try-with-resources.

Encapsuler la logique métier dans une couche Service.

Tester le tout via des classes main() claires et simples.

<img width="815" height="227" alt="image" src="https://github.com/user-attachments/assets/282289df-0a9b-45c4-8e70-548c27700e1f" />
<img width="841" height="213" alt="image" src="https://github.com/user-attachments/assets/a8897a7c-2e38-4f55-b2bd-96f2918401e2" />
