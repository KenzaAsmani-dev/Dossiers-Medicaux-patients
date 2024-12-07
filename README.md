# Dossiers-Medicaux-patients
Cette application nommée SDMPRO aborde le thème de Gestion et suivi des dossiers médicaux des des patients dans un Système hospitalier universitaire. 
### Le Système d'Information Hospitalier (SIH) est très essentiel pour assurer une gestion efficace et sécurisée des établissements de santé, ils permettent à :  
-	Automatiser les processus administratifs. 
-	Collaborer entre les professionnels de santé.
-	Amélioration de la qualité des soins. 
-	Partage sécurisé des données médicales. 
### L’importance de l’informatisation des dossiers médicaux ? 
-	Un enregistrement précis et détaillé des données médicales.
-	Un accès simplifié et une gestion aisée des dossiers médicaux.
-	Une réduction des erreurs médicales.
-	Une collaboration entre le personnel médical et paramédical.
### Technologies utilisées
- Front-end : ReactJS
- Bibliothèques : Material UI, React-Icons, React Router Dom, Formik and Yup, Moment Js, Sweetalert. 
- Back-end : Laravel (version 9)
- Connection entre Front-end et Back-end : ReactQuery et Axios
- Base de données : MySQL
- Environnement de Codage : VS Code, Vite
- Tests : API Postman

### Démarrage de L'application 
#### Coté Serveur 
Dans le terminal, nous écrivons la commande suivante : php artisan serve
#### Coté Client 
Dans le terminal, nous écrivons la commande suivante : npm start

### Installations 
- Pour installer un projet Laravel (Version 9), on écrit la commande suivante : composer create-project laravel/laravel:^9.x  example-app
- Pour installer un projet ReactJS, Nous écrivant la commande suivante : npx create-reat-app <nom_de_votre_projet>

## Controleur
- Pour créer un controleur, utilisez la commande suivante : 
- php  artisan  make:controller  nom_de_votre_controleur
  
#### Exemple
Pour créer une un controleur nommé userController : php artisan make:controller UserController

## Model 
- Pour créer un Model, utilisez la commande suivante : 
- php artisan make:model Nom_de_votre_Modele

#### Exemple
Pour créer une un controleur nommé User : php artisan make:model User


## Migration
- Pour créer une Migration, utilisez la commande suivante : 
- php artisan make:migration nom_de_la_migration

#### Exemple
php artisan make:migration create_users_table

## Seeder
- Pour créer un Seeder, utilisez la commande suivante : 
- php artisan make:seeder nom_de_seeder

#### Exemple
php artisan make:seeder UsersTableSeeder


