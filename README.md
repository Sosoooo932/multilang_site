# Multilingual Django Site

## Description

Ce projet est une structure de base pour un site Django multilingue. En raison de contrainte de ressources, l'implémentation complète n'a pas été réalisée. Cependant, les étapes et la logique prévues sont décrites ci-dessous.

## Étapes de Développement

### 1. Installation et Configuration de Django
- Création de l'environnement virtuel et installation de Django.
- Initialisation du projet Django et de l'application principale.

### 2. Modèles et Vue de Base
- Définition du modèle `Article` pour les articles de blog.
- Création des vues pour afficher la liste des articles.

### 3. Internationalisation
- Configuration de l'internationalisation dans les paramètres du projet.
- Création et compilation des fichiers de traduction.

### 4. Interface Utilisateur
- Création de templates pour afficher les articles de blog.
- Ajout de la fonctionnalité de changement de langue.

### 5. Utilisation de Modèles de Langage (LLM) et RAG (optionnel)
- Intégration d'un chatbot utilisant l'API OpenAI.

## Difficultés Rencontrées
- Limitations techniques et de ressources pour terminer l'implémentation complète.
  

## Instructions pour Exécuter le Projet
1. Cloner le dépôt.
2. Créer un environnement virtuel et installer les dépendances.
3. Appliquer les migrations et lancer le serveur de développement.

```sh
git clone https://github.com/votre-utilisateur/votre-depot.git
cd votre-depot
python -m venv env
source env/bin/activate  # Pour Linux/Mac
.\env\Scripts\activate  # Pour Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
