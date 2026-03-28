# 04 - Spring Security & JWT 🛡️

Ce module se concentre sur la protection de l'application. L'objectif est de contrôler QUI peut accéder à QUOI (Authentification & Autorisation).

## 📚 Programme du cours (OpenClassrooms)

### Partie 1 : Fondations de la Sécurité
* **Filtres de Sécurité** : Comprendre la chaîne de filtres (Security Filter Chain).
* **Configuration de Base** : Désactiver le login par défaut et créer une configuration personnalisée.
* **UserDetailsService** : Charger les utilisateurs depuis la base de données.

### Partie 2 : Authentification & JWT (JSON Web Token)
* **Mécanisme Stateless** : Pourquoi utiliser le JWT plutôt que les sessions (Cookies) ?
* **Génération de Token** : Créer un JWT sécurisé après une connexion réussie.
* **Validation de Token** : Extraire et vérifier le JWT à chaque requête entrante.

### Partie 3 : Autorisations & Rôles
* **RBAC (Role-Based Access Control)** : Différencier les accès USER, ADMIN ou MODERATEUR.
* **Method Security** : Utiliser l'annotation @PreAuthorize pour protéger des méthodes spécifiques.
* **BCrypt** : Hasher les mots de passe pour ne jamais les stocker en clair.

## 🚀 Objectif Technique
Sécuriser les données d'**Epicrafter's Journey**. Seuls les utilisateurs connectés peuvent construire dans l'univers, et seul l'admin peut supprimer des mondes.

## 📝 Notes & Rappels (The Wagon ➔ Spring Security)
* *Devise vs Spring Security* : Au Wagon, Devise gérait tout en arrière-plan. Avec Spring Security, on écrit nous-mêmes notre "SecurityConfig". C'est plus de code, mais une précision chirurgicale sur la sécurité.
* *Stateless* : Comme nous construisons une API pour un futur Front-end (HTMX ou Mobile), nous n'utilisons pas de session serveur, mais des tokens envoyés dans le Header Authorization.
