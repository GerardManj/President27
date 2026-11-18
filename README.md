# 🗳️ President27

> Tu veux voter pour lui ? Ou surtout pas ? Parlons-en, sources à l'appui.

President27 est un site pour **challenger son choix** à la présidentielle 2027. Tu choisis un candidat, tu dis si tu veux voter **pour** ou **contre** lui, et pourquoi. Une IA te répond avec le pour, le contre et le contexte. **Chaque information est sourcée.**

👉 **En ligne : https://president27.vercel.app** (pour l'instant, une première version : un jeu de défis)

## Comment ça marchera

1. Tu choisis un candidat.
2. Tu dis « je veux voter pour » ou « je ne veux pas voter pour », et pourquoi. Par exemple : « Je ne veux pas voter pour ce candidat à cause de sa position sur l'immigration. »
3. L'IA te répond : ce que le candidat propose vraiment sur ce sujet, ce que disent les faits, et le meilleur argument de l'autre côté. Chaque fait est accompagné de son lien.
4. Tu vérifies. L'IA peut se tromper : les sources sont là pour ça.

## Nos règles

- **Neutralité** : ni gauche, ni droite, ni centre, ni libéral, ni communiste. Tous les candidats sont traités de la même façon, que tu sois pour ou contre.
- **Des sources fiables, dans cet ordre** :
  1. sources primaires (programmes, votes au Parlement, déclarations) ;
  2. institutions publiques et statistiques (INSEE, Cour des comptes, Banque de France, OCDE…) ;
  3. recherche académique ;
  4. think tanks, avec leur orientation affichée ;
  5. vérification des faits (AFP Factuel, Les Décodeurs).

  Pas d'émissions, d'éditos ni de réseaux sociaux.
- **Pas de compte, pas de fichage** : les visiteurs n'ont pas de compte. L'opinion politique est une donnée sensible (RGPD) : ton choix et ta question ne sont jamais liés à ton identité. Ta question est transmise à l'IA uniquement pour obtenir la réponse.
- **Pas de diffamation** : l'humour vise les certitudes de l'électeur, jamais la personne du candidat.

## Feuille de route

- [x] Première version en ligne : choisir un candidat, recevoir un défi
- [ ] Charte des sources et gabarit de réponse de l'IA
- [ ] Test de l'IA à la main sur des questions types
- [ ] Nouvelle page : candidat → pour ou contre → pourquoi → réponse de l'IA
- [ ] Brancher l'IA côté serveur, avec un plafond de dépenses
- [ ] Back-office admin (connexion Google) : gérer les sources
- [ ] Icônes pixel art des candidats, en commençant par les plus populaires
- [ ] Liste officielle des candidats, après les parrainages

## Lancer le projet sur son ordinateur

Il faut [Node.js](https://nodejs.org) (qui installe aussi npm).

```bash
npm install      # télécharge les outils du projet (ici : Vite)
npm run dev      # lance le site en local, avec rechargement automatique
npm run build    # fabrique la version finale du site dans dist/
```

## Les outils

| Outil | Rôle |
|---|---|
| HTML, CSS, JavaScript | Le site lui-même (`index.html`) |
| [Vite](https://vite.dev) | Serveur local et fabrication du site |
| Git et GitHub | Historique du code, branches et Pull Requests |
| [Vercel](https://vercel.com) | Hébergement : chaque merge dans `main` met le site à jour |
| À venir | L'API Claude pour l'IA, une base de données pour les sources |

Le code est écrit avec [Claude Code](https://claude.com/claude-code), puis relu et validé à chaque étape.
