# 📝 Gestion de tâches - Symfony 7.1

Ce projet est une application de gestion de tâches développée avec **Symfony 7.1**.  
Elle permet de créer, modifier, marquer comme terminées ou supprimer des tâches.  
L'interface utilisateur est conçue pour être **responsive** grâce à Bootstrap.

---

## 🚀 Fonctionnalités

- **Ajouter des tâches** : Saisissez un titre et une description pour une nouvelle tâche.
- **Modifier des tâches** : Mettez à jour les informations des tâches existantes.
- **Statut des tâches** : Marquez les tâches comme terminées ou en attente.
- **Supprimer des tâches** : Supprimez les tâches qui ne sont plus nécessaires.
- **Recherche** : Trouvez rapidement une tâche en fonction de mots-clés (titre ou description).
- **Pagination** : Visualisez les tâches par pages pour une meilleure organisation.
- **Tri par id** : Affichez les tâches dans un ordre décroissant par id.
- **Interface moderne** : Utilisation de Bootstrap pour un design propre et responsive.

---

## 🛠️ Prérequis

Avant de commencer, assurez-vous d'avoir les outils suivants installés sur votre machine :

- **PHP** : Version 8.2 ou supérieure.
- **Composer** : Pour la gestion des dépendances PHP.
- **MySQL** : Pour la base de données.
- **Symfony CLI** : Optionnel mais recommandé pour gérer l'environnement de développement.

---

## ⚙️ Installation

1. **Clonez le dépôt :**

   ```bash
   git clone https://github.com/WebAlexSolutions/todolist_project.git
   cd todolist_project

2. **Installez les dépendances PHP avec Composer :**

   ```bash
   composer install

3. **Configurez la base de données dans le fichier .env :**
  Ouvrez le fichier .env et remplacez la valeur de DATABASE_URL par vos informations de connexion.
   ```bash
   DATABASE_URL="mysql://username:password@127.0.0.1:3306/nom_de_la_base?serverVersion=8.0.32&charset=utf8mb4"
   
  * **username :** Nom d'utilisateur pour accéder à MySQL.
  * **password :** Mot de passe de l'utilisateur MySQL.
  * **nom_de_la_base :** Nom de la base de données que vous souhaitez utiliser pour l'application.

4. **Créez la base de données et exécutez les migrations :**

   Pour créer la base de données et appliquer les migrations nécessaires à la structure de la base de données, utilisez les commandes suivantes :
   ```bash
   php bin/console doctrine:database:create
   php bin/console doctrine:migrations:migrate

5. **Démarrez le serveur Symfony :**

   Une fois toutes les étapes précédentes terminées, démarrez le serveur de développement Symfony en exécutant la commande suivante :
   ```bash
   symfony server:start

6. **Accédez à l'application :**
   
   Ouvrez votre navigateur et rendez-vous sur l'adresse suivante pour voir l'application en action :
   ```bash
   http://localhost:8000

## 🎯 Utilisation

1. Sur la page d'accueil, visualisez les tâches existantes avec pagination.
2. Ajoutez une tâche via le bouton **Nouvelle tâche** (ouvre un formulaire dans une modale).
3. Utilisez la barre de recherche pour filtrer les tâches par mot-clé.
4. Modifiez ou supprimez les tâches via les options de la liste.

---

## 🧰 Technologies utilisées

- **Framework** : Symfony 7.1
- **Base de données** : MySQL
- **Frontend** : Bootstrap 5 et Bootstrap Icons
- **Pagination** : KnpPaginatorBundle

---

## 📸 Aperçu

**Liste des tâches :**

![image](https://github.com/user-attachments/assets/a0b251a1-be49-40dd-8d02-c2ab8d9971cb)

**Ajouter une nouvelle tâche :**

![image](https://github.com/user-attachments/assets/eb7a7f3f-a468-41bb-a29b-36edc3ed327e)

**Les différentes actions proposées :**

![image](https://github.com/user-attachments/assets/b95e2098-b9dc-425e-acf9-d580ad02325f)

**Voir une tâche :**

![image](https://github.com/user-attachments/assets/9370f0e8-5259-4a6b-81cb-dfbb1076cfaa)

**Editer une tâche :**

![image](https://github.com/user-attachments/assets/d5bc7105-5a21-4b07-a058-eec3b7b2f821)

---

## 📜 Licence

**© 2024 WebAlex Solutions - Tous droits réservés.**

---

## 👤 Contributeurs

- **Alexandre** - Développeur principal ([WebAlex Solutions](https://www.webalexsolutions.fr))

---

## 🔗 Liens utiles

- Symfony : [https://symfony.com/](https://symfony.com/)
- Bootstrap : [https://getbootstrap.com/](https://getbootstrap.com/)
- WebAlex Solutions : [https://www.webalexsolutions.fr](https://www.webalexsolutions.fr)

