# 🗳️ President27 — Tableau de bord des missions

**XP total : 500** · **Niveau : 🐣 Militant du dimanche** (prochain niveau à 800)

> Niveaux : 🥚 Électeur indécis (0) → 🐣 Militant du dimanche (300) → 🦅 Tracteur de tracts (800) → 🎤 Tribun du web (1500) → 🏛️ Président·e du code (2500)

Chaque mission : 🎯 objectif · 🔍 code expliqué · 🧠 mini-quiz · 🤖 réflexe IA · ✅ preuve.
Une mission est cochée seulement quand sa **preuve** est vérifiée. Les ⭐ quêtes bonus sont facultatives (+50 XP).

## 📌 Pense-bête

- [ ] **Mettre à jour la liste des candidats** (dans `index.html`, puis dans la table `candidats` à partir de J8). Source : [Wikipédia, « Candidatures à l'élection présidentielle française de 2027 »](https://fr.wikipedia.org/wiki/Candidatures_%C3%A0_l%27%C3%A9lection_pr%C3%A9sidentielle_fran%C3%A7aise_de_2027), tableau « Candidats déclarés ». Dernière version reprise : **13/11/2026** (29 candidats). La liste officielle (après les parrainages) sera publiée par le Conseil constitutionnel avant le 1er tour du 18/04/2027. Penser à changer aussi la date dans le pied de page.

---

## Semaine 1 — Mettre un site en ligne

- [x] **J1 · Hello, monde** (100 XP + ⭐ 50) ✅ 16/11 — `index.html` ouvert dans le navigateur, un texte modifié par toi. Réflexe IA : faire expliquer, créer `CLAUDE.md`.
  - ⭐ Bonus : ouvrir les outils de développement du navigateur (F12) et changer une couleur en direct.
- [x] **J2 · Git local** (100 XP) ✅ 16/11 — `git log` avec ≥ 3 commits. Réflexe IA : relire chaque diff.
- [x] **J3 · GitHub** (100 XP) ✅ 16/11 — code visible sur github.com. Réflexe IA : jamais de secret dans le chat.
- [x] **J4 · Vercel** (150 XP) ✅ 16/11 — URL `*.vercel.app` publique : https://president27.vercel.app. Réflexe IA : faire diagnostiquer les logs d'erreur.
- [ ] **J5 · Le jeu v0** (150 XP) — choisir un candidat → recevoir un défi, via une Pull Request. Réflexe IA : planifier avant de coder.
- [ ] **J6 · Node & npm** (100 XP) — `npm run dev` + déploiement OK. Réflexe IA : vérifier dans la doc officielle.
- [ ] **J7 · 👹 Boss : rétro & README** (200 XP) — README propre, journal à jour. Réflexe IA : code review par l'IA, tu tranches.

## Semaine 2 — Données & utilisateurs

- [ ] **J8 · Supabase** (100 XP) — tables `candidats` et `defis` créées en SQL.
- [ ] **J9 · Lire la base** (150 XP) — le site affiche les défis depuis la base (RLS activée).
- [ ] **J10 · Écrire dans la base** (150 XP) — un visiteur peut proposer un défi / voter.
- [ ] **J11 · Authentification** (150 XP) — connexion par lien magique, données sensibles protégées.
- [ ] **J12 · Page stats** (100 XP) — classement des défis via une vue SQL.
- [ ] **J13 · Tests & CI** (150 XP) — un test qui tourne automatiquement sur chaque PR.
- [ ] **J14 · 👹 Boss : rétro & refacto** (200 XP)

## Semaine 3+ — Le bot satirique (esquisse)

- [ ] Fonction serveur qui appelle l'API Claude (clé côté serveur uniquement)
- [ ] Prompt système du bot : drôle, équitable, sans diffamation
- [ ] Évals du bot
- [ ] Mode sérieux : faits sourcés en base pour appuyer la satire
- [ ] Coûts & limites

---

## 🏅 Badges

| Badge | Condition | Obtenu |
|---|---|---|
| 🏁 Premier pas | Terminer J1 | ✅ 16/11 |
| 📸 Photographe | Premier commit | ✅ 16/11 |
| 🌍 En ligne ! | Site public sur Vercel | ✅ 16/11 |
| 🔀 Diplomate | Première Pull Request mergée | |
| 🗄️ Archiviste | Première ligne en base | |
| 🔐 Gardien | Auth fonctionnelle | |
| 🧠 Sans faute | Un mini-quiz réussi à 100 % | ✅ 16/11 |
| 🤖 Dompteur d'IA | Le bot satirique répond en ligne | |
