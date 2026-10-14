# PR-Inscription

PR-Inscription est un projet de plateforme web destiné à simplifier la préinscription des élèves dans les établissements secondaires. Les parents pourront transmettre les informations et les pièces nécessaires en ligne, puis suivre l'avancement de leur dossier. Le personnel administratif pourra consulter les demandes, les traiter et, si le dossier est accepté, proposer un rendez-vous pour finaliser l'inscription sur place.

## Contexte

Les démarches d'inscription entraînent souvent plusieurs déplacements et de longues heures consacrées aux tâches administratives. La plateforme vise à permettre aux parents de préparer le dossier à distance et à faciliter son traitement par les établissements. La validation définitive de l'inscription reste effectuée par l'établissement.

## Objectifs

- Simplifier la préparation et le dépôt des dossiers de préinscription.
- Permettre aux parents de consulter l'état d'avancement de leur demande.
- Aider le personnel administratif à centraliser et traiter les dossiers.
- Organiser la finalisation de l'inscription en présentiel, sur rendez-vous lorsque cela est nécessaire.
- Réduire les déplacements et le temps d'attente liés aux démarches.

## Parcours envisagé

1. Le parent renseigne les informations demandées et dépose les pièces  justificatives.
2. L'établissement consulte le dossier et le traite.
3. Le parent est informé de la décision ou des éventuelles pièces à compléter.
4. Si le dossier est retenu, un rendez-vous peut être proposé pour finaliser l'inscription auprès de l'établissement.

## Stack technique envisagée

Les technologies ci-dessous sont prévues pour le projet ; elles ne signifient pas nécessairement qu'elles sont déjà toutes intégrées.

| Technologie | Rôle prévu |
| --- | --- |
| React, Vite et TypeScript | Créer une interface web moderne et bénéficier du typage statique. |
| Node.js, Express et TypeScript | Développer l'API et partager TypeScript entre le client et le serveur. |
| PostgreSQL | Stocker les données relationnelles : parents, élèves, dossiers et pièces justificatives. |
| Prisma | Décrire le modèle de données et gérer les migrations de la base. |
| Zod | Valider les données saisies et reçues par l'application. |
| Docker Compose | Simplifier le lancement des services nécessaires au développement, notamment PostgreSQL. |
| Vercel ou Netlify | Envisager l'hébergement de l'interface pour une démonstration en ligne. |

## État du projet

Projet d'apprentissage en cours de construction. Les fonctionnalités et la stack présentées dans ce document décrivent les objectifs envisagés et peuvent évoluer au fil du développement.
