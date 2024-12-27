# YAML2Code : Générateur Automatique de Code 

## Description Générale

**YAML2Code** est une application open-source permettant aux développeurs de transformer un fichier YAML décrivant une application en code source fonctionnel. Le processus est simple :  
1. L'utilisateur charge un fichier YAML.  
2. Il sélectionne le framework cible (Spring Boot, React.js, Flask).  
3. L'application génère automatiquement le code correspondant.

## Caractéristiques principales

1. **Support Multiframework**
   - **Back-end** : Spring Boot (Java), Flask (Python).
   - **Front-end** : React.js (JavaScript/TypeScript).

2. **API RESTful**
   - Permet une intégration facile avec d'autres outils et pipelines CI/CD.
   - Possibilité d'envoyer un fichier YAML via l'API pour automatiser la génération de code.

3. **Interface Utilisateur **
   - **Uploader de fichier YAML** : Facilité de chargement du fichier YAML via l'interface graphique.
   - **Aperçu du code généré** : Visualisation du code .


## Impact

- **Gains de temps significatifs** : Automatisation des tâches fastidieuses liées à l'initialisation des projets.
- **Uniformité et Qualité** : Promeut des structures de code conformes aux standards des frameworks populaires.
- **Démocratisation** : Accessible même aux développeurs débutants pour générer rapidement des bases de projets solides.

## Architecture Fonctionnelle

1. **Back-end**
   - **Langage** : Spring Boot (Java).
   - **Fonctionnalités** :  
     - API RESTful pour gérer les fichiers YAML.
     - 
2. **Front-end**
   - **Framework** : React.js (TypeScript/JavaScript).
   - **Interface Utilisateur** :  
     - Chargement de fichiers YAML.
     - Sélection du framework cible via un menu déroulant.
     - Visualisation du code généré.

3. **Générateur de Code**
   - Module central responsable de la lecture du YAML et de la transformation en code.

4. **Traitement des Fichiers**
   - Validation du fichier YAML pour vérifier sa conformité.
   - Adaptation des templates spécifiques à chaque framework.

## Workflow Utilisateur

1. Charge un fichier YAML via l'interface ou l'API.
2. Sélectionne le framework cible (par ex. Spring Boot).
3. Visualise le code généré directement dans l'interface .

## Prochaines Étapes

1. **Prototype** :
   - Implémentation de base pour Spring Boot avec un exemple simple (CRUD).
2. **Tests** :
   - Vérification des fichiers YAML d'entrée et des structures générées.
3. **Extensibilité** :
   - Ajout du support pour React.js et Flask.
4. **Optimisation UX/UI** :
   - Création d’un éditeur YAML interactif intégré à l’interface.

Avec ce plan, YAML2Code deviendra une solution puissante et polyvalente pour les développeurs cherchant à accélérer leurs cycles de développement tout en produisant un code de qualité.
## video démonstration :
https://github.com/user-attachments/assets/12e76496-b699-44f1-ba11-573771f95b28


