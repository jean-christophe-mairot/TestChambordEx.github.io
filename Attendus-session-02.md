# Atelier professionnel 3 — Hôtel Chambordù

Contexte  
Un client propriétaire du relais-château "Hôtel Chambord" a commandé la finalisation du site web frontend (technologies : HTML, CSS, JavaScript, Bootstrap). Il fournira un poste de travail sur lequel le site devra être installé et rendu opérationnel : système d'exploitation Linux et serveur LAMP installés et fonctionnels. L'équipe devra livrer le site responsive, les pages de connexion et les formulaires Bootstrap prêts à être exploités par le backend, et procéder à la mise en production sur github.

## 2. Corrections du site et mise en place de Trello

### Trello

- Établir les rôles : chef de projet, référent SLAM, référent SISR.
- Évaluer collectivement les tâches à produire.
- Répartir les tâches entre les membres.
- Intégrer un diagramme de Gantt dans la documentation (évaluation des durées des tâches par personne sur la durée de l'AP).

- Effectuer une batterie de tests pour détecter et corriger les erreurs éventuelles du site web du client.

## 3. Création des pages (voir la maquette dans le dossier ref de l'AP)

- Page Réservations : page liée aux boutons des pages Chambre, SPA, Restaurant (conception de formulaires).
- Page de connexion : proposer un design cohérent avec le site ; ajouter un lien/une icône dans la navigation qui fait le lien vers la page connexion.
- Page Recrutements : design cohérent ; accessible depuis la page Contact.
- Page Activités (remplace la page actualites) : réaliser selon la maquette.
- Page Avis : ajouter un formulaire de dépôt d'avis (non fonctionnel).
- page 404 : proposer un design cohérent avec le site

pages de préparation pour le backend :

- Page Modification de compte : créer une page permettant aux utilisateurs de modifier leurs informations personnelles (nom, prénom, email, mot de passe). Cette page doit inclure un formulaire. Ajouter un champ caché pour la récupération de l'ID client afin de faciliter la mise à jour des données côté serveur. Le design doit être cohérent avec le reste du site.
- Page Creation emplois : créer une page permettant de gérer les offres d'emploi. Cette page doit inclure un formulaire pour ajouter une nouvelle offre d'emploi (titre, description, compétences requises, etc.) et afficher la liste des offres existantes. Le design doit rester cohérent avec le reste du site.
- Page Gestion des utilisateurs et services : créer une page permettant à l'administrateur du site de gérer les comptes clients, les services, et les comptes administrateurs. Cette page doit inclure les fonctionnalités suivantes :
  - Ajouter un compte client, un service, ou un compte administrateur via un formulaire (champs requis : nom, prénom, email, mot de passe, rôle, etc.).
  - Modifier les informations existantes des comptes ou des services.
  - Afficher la liste des comptes clients, des services, et des administrateurs avec des options pour les trier et les rechercher.
  - Supprimer un compte ou un service avec une confirmation avant suppression.
  - Le design de cette page doit être cohérent avec le reste du site.

## 4. Installation Linux

- Créer une clé USB bootable.
- Installer la machine Linux (validation par l'enseignant).
- Rédiger une documentation pas à pas de l'installation pour le client.
- Rédiger un tutoriel de création d'une session sous Linux (interface graphique et lignes de commande).
- Mettre en place un serveur web sur la machine Linux (serveur LAMP).
- Rédiger un tutoriel d'installation et de configuration du serveur LAMP.

## Livrables et documentation remis au client

- Restitution du site complet au format ZIP en conservant l'architecture d'origine (naming : AP3_nomEleve1_nomEleve2_nomEleve3.zip).
- Mise en production sur GitHub : chaque élève publie sur son dépôt et fournit le lien dans la documentation globale.
- Documentation globale du projet incluant :
  - gestion de projet (Trello, rôles, Gantt),
  - description du site web (structure, pages, assets),
  - procédure d'installation de la machine Linux,
  - configuration et installation du serveur web (LAMP),
  - procédures de mise en production (GitHub).
- Vérifier que tous les liens et chemins fonctionnent en production avant remise.
- Fournir une checklist de validation pour l'enseignant et le client.
