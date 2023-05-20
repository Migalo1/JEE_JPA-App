# JEE_JPA-App

Ce référentiel contient une application JEE (Java Enterprise Edition) utilisant JPA (Java Persistence API). L'application démontre l'utilisation de JPA pour la persistance des données dans une base de données relationnelle.

## Prérequis

Avant de pouvoir exécuter l'application, vous devez vous assurer que les éléments suivants sont installés sur votre système :

- Java Development Kit (JDK) version 8 ou supérieure
- Serveur d'applications compatible JEE (comme Apache Tomcat ou WildFly)
- SGBD relationnel (comme MySQL, PostgreSQL ou Oracle)

## Configuration

Suivez les étapes ci-dessous pour configurer et exécuter l'application :

1. Clonez ce référentiel sur votre machine locale :

   ```
   git clone https://github.com/Migalo1/JEE_JPA-App.git
   ```

2. Ouvrez le projet dans votre environnement de développement préféré.

3. Configurez le serveur d'applications JEE en fonction de votre choix (Tomcat, WildFly, etc.).

4. Créez une base de données vide dans votre SGBD relationnel.

5. Configurez les paramètres de connexion à la base de données dans le fichier `persistence.xml` situé dans le répertoire `src/main/resources/META-INF`. Modifiez les propriétés `javax.persistence.jdbc.url`, `javax.persistence.jdbc.user` et `javax.persistence.jdbc.password` selon votre configuration.

6. Exécutez les scripts SQL fournis dans le répertoire `src/main/resources/sql` pour créer les tables nécessaires dans la base de données.

7. Compilez et déployez l'application sur le serveur d'applications.

8. Lancez le serveur d'applications et accédez à l'URL de déploiement spécifique pour utiliser l'application.

## Fonctionnalités

L'application JEE_JPA-App propose les fonctionnalités suivantes :

- Création, lecture, mise à jour et suppression (CRUD) d'entités dans la base de données.
- Utilisation de transactions pour garantir l'intégrité des données.
- Mapping objet-relationnel avec JPA à l'aide d'annotations.

## Structure du projet

Le projet est structuré de la manière suivante :

- Le répertoire `src/main/java` contient le code source de l'application.
- Le répertoire `src/main/resources` contient les ressources de l'application, telles que les fichiers de configuration.
- Le répertoire `src/main/webapp` contient les fichiers Web pour l'interface utilisateur de l'application.

## Contributions

Les contributions à ce projet sont les bienvenues. Si vous souhaitez apporter des améliorations, veuillez soumettre une demande de fusion (pull request) en décrivant clairement les modifications proposées.

## Licence

Ce projet est sous licence MIT. Veuillez consulter le fichier `LICENSE` pour plus d'informations.

---
*Remarque : Ce README est généré à titre informatif. N'oubliez pas de mettre à jour le fichier README en fonction de votre projet spécifique.*
