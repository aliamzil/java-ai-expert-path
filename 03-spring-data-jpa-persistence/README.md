# 03 - Spring Data JPA & Persistence 🗄️

Ce module transforme les objets Java en tables de base de données. L'objectif est de persister les données de l'application de manière industrielle.

## 📚 Programme du cours (OpenClassrooms)

### Partie 1 : Connexion & Configuration
* **Configuration DataSource** : Paramétrer l'URL, le login et le mot de passe de la BDD.
* **Hibernate & JPA** : Comprendre le rôle de l'ORM (Object-Relational Mapping).
* **Docker Compose** : Lancer une instance PostgreSQL localement en une commande.

### Partie 2 : Modélisation des Entités
* **Annotations d'Entité** : @Entity, @Id, @GeneratedValue, @Column.
* **Relations Unidirectionnelles** : @OneToOne, @ManyToOne.
* **Relations Bidirectionnelles** : @OneToMany, @ManyToMany et la gestion du "MappedBy".

### Partie 3 : Manipulation des Données (CRUD)
* **Interface Repository** : Étendre CrudRepository et JpaRepository.
* **Query Methods** : Créer des requêtes automatiques par le nom de la méthode (ex: findByName).
* **Requêtes Personnalisées** : Utiliser l'annotation @Query et le langage JPQL.

## 🚀 Objectif Technique
Persister l'univers d'**Epicrafter's Journey** dans une base SQL. Chaque bloc construit doit être sauvegardé et récupérable après un redémarrage du serveur.

## 📝 Notes & Rappels (The Wagon ➔ Spring Data)
* *Active Record vs Data Mapper* : En Rails, l'objet User connaît la base de données (User.save). En Java, l'objet User est une simple donnée (POJO), et c'est le **UserRepository** qui s'occupe de la sauvegarde.
* *Migrations* : Au lieu de bin/rails db:migrate, on utilisera souvent **Flyway** ou **Liquibase** pour gérer les versions du schéma SQL.
