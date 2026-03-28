# 06 - Reactive Frontend with HTMX ⚡

Ce module donne une interface utilisateur à l'application. L'objectif est de créer une expérience fluide et dynamique sans la complexité d'un framework JavaScript lourd.

## 📚 Programme du cours (Expert AI Path)

### Partie 1 : Thymeleaf & Layouts
* **Moteur de Template** : Utiliser Thymeleaf pour générer du HTML dynamique.
* **Fragments & Layouts** : Créer des composants réutilisables (Navbar, Sidebar, Cards).
* **Tailwind CSS** : Styliser l'application rapidement avec des classes utilitaires.

### Partie 2 : HTMX - Le "JavaScript sans JavaScript"
* **Requêtes AJAX Natives** : Utiliser hx-get, hx-post pour mettre à jour des parties de la page sans rechargement.
* **Indicateurs de chargement** : Gérer les feedbacks visuels pendant les appels à l'IA.
* **Validation en temps réel** : Valider les formulaires Java au fur et à mesure de la saisie.

### Partie 3 : WebSockets & Server-Sent Events (SSE)
* **Streaming de l'IA** : Afficher la réponse de l'IA mot par mot (comme sur ChatGPT).
* **Notifications Push** : Envoyer des alertes au navigateur depuis le serveur Java.
* **Interactivité temps réel** : Mettre à jour l'univers d'Epicrafter instantanément pour tous les utilisateurs.

## 🚀 Objectif Technique
Lancer le **Dashboard d'Epicrafter**. Une interface sombre et moderne (Glassmorphism) où l'on peut discuter avec l'Oracle (IA), gérer son inventaire et voir ses constructions se mettre à jour en direct.

## 📝 Notes & Rappels (The Wagon ➔ HTMX)
* *Exit le JS complexe* : Contrairement à React, HTMX renvoie du **HTML** directement. Pas de JSON à parser côté front, pas de State Management complexe. C'est le retour à la simplicité du Web, dopé aux stéroïdes.
* *Productivité* : On reste dans l'écosystème Java/Spring. Pas besoin de gérer deux serveurs (un pour le front, un pour le back).
