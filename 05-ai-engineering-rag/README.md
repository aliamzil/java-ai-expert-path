# 05 - AI Engineering & RAG 🤖

Ce module intègre l'Intelligence Artificielle générative au cœur de l'application Java. L'objectif est de créer un agent intelligent capable de raisonner sur les données du projet.

## 📚 Programme du cours (Expert AI Path)

### Partie 1 : Introduction à Spring AI
* **Concepts LLM** : Comprendre les Prompts, Tokens et Température.
* **Spring AI Starter** : Configurer les clients OpenAI ou Ollama (local).
* **ChatClient & Prompt Templates** : Créer des interactions structurées avec l'IA.

### Partie 2 : Vector Databases & Embeddings
* **Embeddings** : Transformer du texte en vecteurs mathématiques.
* **pgvector** : Installer l'extension vectorielle sur PostgreSQL.
* **Vector Stores** : Stocker et rechercher des documents par similarité sémantique.

### Partie 3 : Implémentation du RAG (Retrieval-Augmented Generation)
* **Document ETL** : Lire, découper (Chunking) et indexer des fichiers ou des données BDD.
* **Retrieval Strategy** : Récupérer le contexte pertinent pour enrichir la question de l'utilisateur.
* **Function Calling** : Permettre à l'IA d'exécuter des méthodes Java (ex: "Quel est le statut du projet ?").

## 🚀 Objectif Technique
Créer l'**Oracle d'Epicrafter**. Un chatbot intégré qui peut répondre à des questions précises sur l'univers du jeu en consultant la base de données en temps réel via pgvector.

## 📝 Notes & Rappels (The Wagon ➔ AI Engineer)
* *IA Déterministe* : En Java, on encadre l'IA avec des types stricts pour éviter les hallucinations et garantir que les réponses respectent le format JSON attendu par le Front-end.
* *Local vs Cloud* : Nous apprendrons à switcher entre un modèle puissant (Cloud) et un modèle privé (Local avec Ollama) sans changer le code.
