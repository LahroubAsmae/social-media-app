# Social Media App - Fichier de Dépendances

## Modules à Développer

1. Gestion des Utilisateurs
2. Gestion des Posts
3. Gestion des Commentaires
4. Interaction Sociale
5. Recherche et Filtrage
6. Notifications
7. Messages Directs (DM)
8. Bookmarks

## Fonctionnalités par Module

### Gestion des Utilisateurs

#### Inscription et Connexion
- Formulaire d'inscription et de connexion avec validation (Lucia Auth, Next.js).
- Authentification avec gestion des sessions (Lucia Auth, JWT).
- Gestion des erreurs et confirmations.

#### Gestion des Profils
- Interface de profil utilisateur pour modification (Next.js, Tailwind CSS).
- Mise à jour et validation des informations personnelles.

### Gestion des Posts

#### Création de Post
- Formulaire pour créer des posts avec titre et contenu (TipTap Editor, UploadThing).
- Téléchargement de fichiers avec support drag & drop et copier-coller.

#### Affichage des Posts
- Page d'accueil avec flux infini pour posts (TanStack React Query, Infinite Scrolling).
- Affichage des posts avec mentions et hashtags (Postgres DB, Prisma ORM).

#### Modification et Suppression de Post
- Interface pour modifier et supprimer des posts (Next.js, Tailwind CSS).

### Gestion des Commentaires

#### Ajout de Commentaire
- Interface pour ajouter des commentaires aux posts (Next.js, Tailwind CSS).

#### Affichage des Commentaires
- Affichage des commentaires associés aux posts.

#### Modification et Suppression de Commentaire
- Fonctionnalités pour modifier et supprimer des commentaires.

### Interaction Sociale

#### Likes et Suivi
- Système de likes pour posts et commentaires (Next.js, TanStack React Query).
- Suivi d'utilisateurs et gestion des abonnements (Lucia Auth, Postgres DB).

### Recherche et Filtrage

#### Recherche de Posts
- Barre de recherche pour posts avec contenu et hashtags (Full-Text Search, Postgres DB).

#### Recherche d'Utilisateurs
- Barre de recherche pour utilisateurs par nom ou email.

### Notifications

#### Système de Notifications
- Envoi de notifications pour nouveaux posts, commentaires, et suivis (Next.js, TanStack React Query).

### Messages Directs (DM)

#### Chat en Temps Réel
- Interface de messagerie directe avec notifications pour nouveaux messages (Stream, Next.js).
- Historique des conversations et gestion des groupes de discussion (Stream, Next.js).

### Bookmarks

#### Système de Bookmarks
- Permettre aux utilisateurs de sauvegarder et consulter leurs posts favoris.

## Tâches par Fonctionnalité

### Gestion des Utilisateurs

#### Inscription et Connexion
- Développer les formulaires d'inscription et de connexion (Frontend, Backend).
- Configurer l'authentification (Backend).
- Gérer les erreurs et les succès (Frontend, Backend).

#### Gestion des Profils
- Créer et mettre à jour les interfaces de profil (Frontend, Backend).
- Valider et stocker les informations de profil (Backend).

### Gestion des Posts

#### Création de Post
- Développer les formulaires et interfaces pour la création de posts (Frontend).
- Implémenter le support des fichiers (Backend, UploadThing).

#### Affichage des Posts
- Mettre en place le flux infini (Frontend, TanStack React Query).
- Afficher les posts avec les hashtags et mentions (Backend, Postgres DB).

#### Modification et Suppression de Post
- Développer les fonctionnalités pour modifier et supprimer des posts (Frontend, Backend).

### Gestion des Commentaires

#### Ajout, Affichage, Modification et Suppression de Commentaires
- Implémenter les interfaces et logiques pour les commentaires (Frontend, Backend).

### Interaction Sociale

#### Likes et Suivi
- Développer les systèmes de likes et de suivi (Frontend, Backend).

### Recherche et Filtrage

#### Recherche de Posts et Utilisateurs
- Développer les fonctionnalités de recherche avec Full-Text Search (Backend, Postgres DB).

### Notifications

#### Envoi de Notifications
- Mettre en place les notifications pour diverses activités (Backend).

### Messages Directs (DM)

#### Chat en Temps Réel
- Implémenter le système de chat en temps réel (Frontend, Backend, Stream).

### Bookmarks

#### Système de Bookmarks
- Développer la fonctionnalité de gestion des favoris (Frontend, Backend).

---
