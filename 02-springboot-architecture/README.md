# 02 - Spring Boot Architecture 🚀

Ce module marque le passage du code local à une application client-serveur. Nous utilisons Spring Boot pour créer des API REST industrielles.

## 📚 Programme du cours (OpenClassrooms)

### Partie 1 : Fondations de Spring Boot
* **Inversion de Contrôle (IoC)** : Comprendre comment Spring gère le cycle de vie des objets.
* **Injection de Dépendances** : Utiliser @Autowired et les constructeurs pour lier les composants.
* **Architecture en couches** : Séparer le Controller, le Service et le Repository (Modèle MVC).

### Partie 2 : Créer une API REST
* **Controllers** : Gérer les requêtes HTTP (@GetMapping, @PostMapping).
* **DTO (Data Transfer Objects)** : Sécuriser les données entrantes et sortantes.
* **Validation des données** : Utiliser Hibernate Validator pour valider les inputs.

### Partie 3 : Gestion de la configuration
* **Application.properties / YAML** : Paramétrer l'application (Port, Profils dev/prod).
* **Logging** : Suivre l'exécution de l'application en console.
* **Tests unitaires** : Utiliser JUnit et Mockito pour garantir la qualité du code.

## 🚀 Objectif Technique
Transformer le moteur logique d'**Epicrafter's Journey** en une API accessible via des requêtes HTTP (Postman/Insomnia).

## 📝 Notes & Rappels (The Wagon ➔ Spring Boot)
* *Spring Boot vs Rails* : Spring est plus "explicite". Là où Rails faisait de la "magie" (conventions), Spring utilise des **Annotations** (@Service, @Component) pour configurer le comportement.
* *Serveur embarqué* : Contrairement à Ruby qui nécessite un serveur externe (Puma), Spring Boot embarque directement **Tomcat** dans le fichier JAR.
