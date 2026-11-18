# CLAUDE.md — Instructions pour Claude sur ce projet

## Le projet
President27 : un site qui **challenge le choix de vote** à la présidentielle 2027. Le visiteur choisit un candidat, dit s'il veut voter **pour** ou **contre** lui et pourquoi. Une **IA** lui répond avec le pour, le contre et le contexte, toujours **sourcés**. Humour dans la forme, rigueur dans le fond.
**Le but est de construire un vrai site, utile pendant la campagne** (jusqu'au 2d tour, au printemps 2027).

## Décisions prises (18/11/2026)
- **Visiteurs anonymes**, sans compte. La connexion (Google) sert **uniquement au back-office admin**.
- **L'IA est le cœur du site** : elle puise dans des sources prévues à l'avance et peut aussi chercher sur le web. Toute information qu'elle donne cite sa source (lien). Un avertissement visible rappelle que l'IA peut se tromper et qu'il faut vérifier les sources.
- La clé d'API de l'IA reste **côté serveur**, jamais dans le navigateur.
- Candidats affichés **en texte** pour l'instant. Pixel art plus tard, dans un atelier dédié, en commençant par les candidats les plus populaires.

## Qui je suis
Data analyst (SQL, bases de JavaScript), **pas développeur**. C'est mon premier projet complet.

## Comment on travaille
- Réponds en **français**.
- **Claude écrit le code**, je ne tape pas de code. Après chaque changement, explique **seulement les passages clés**.
- **Explique simplement les pratiques que tu mets en place** : ce que c'est et pourquoi, en 1 à 3 phrases, sans jargon (ou jargon expliqué).
- Quand une bonne pratique de travail avec l'IA apparaît, signale-la en une phrase.
- Je fais les étapes qui passent par mes comptes : créer les comptes, cliquer dans les interfaces (GitHub, Vercel, Supabase…). Si tu peux le faire à ma place, dis-le-moi.
- **Git** : Claude fait les commandes de routine (`status`, `add`, `commit`, `log`, `diff`) en disant en une phrase ce que fait chacune. Je garde : lire le diff, décider quand commiter, valider toute commande destructrice ou qui part sur internet (`push`, `reset`, suppressions). Antisèche : `GIT.md`.
- **Petits pas** : une étape à la fois. N'ajoute pas un outil ou une librairie sans m'expliquer d'abord pourquoi on en a besoin.

## Règles du site
- **Neutralité** : ni gauche, ni droite, ni centre, ni libéral, ni communiste. Tous les candidats sont traités de la même façon (mêmes questions, même format, même nombre de faits).
- **Factuel et sourcé** : toute affirmation factuelle a une source, datée. Ordre de préférence : 1) sources primaires (programme, votes au Parlement, déclarations du candidat) ; 2) institutions publiques et statistiques (INSEE, Cour des comptes, COR, Banque de France, OCDE…) ; 3) recherche académique ; 4) think tanks, avec leur orientation affichée, idéalement deux orientations opposées sur un même sujet ; 5) vérification des faits (AFP Factuel, Les Décodeurs). Exclus : émissions, éditos, réseaux sociaux.
- Pas de propos diffamatoires, pas de fausses informations présentées comme vraies. L'humour vise les certitudes de l'électeur, jamais la personne du candidat.
- **RGPD** : l'opinion politique est une donnée sensible. Ne jamais lier intention de vote et identité.

## Fichiers personnels (ignorés par Git, jamais commités)
- `APPRENTISSAGES.md` : concepts clés et points pas encore compris.
- `MISSIONS.md` : ancien plan d'apprentissage, sert de base pour la feuille de route.
