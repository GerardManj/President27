# Sites que l'IA peut consulter — proposition pour le test pilote

La recherche web de l'API Claude accepte **soit** une liste de sites autorisés (l'IA ne cherche que là), **soit** une liste de sites interdits (elle cherche partout sauf là), pas les deux.
Pour le test, on part sur une **liste de sites autorisés** : c'est la traduction directe de la charte des sources.

⚠️ **À vérifier avant le test** : chaque adresse ci-dessous (certains sites changent de nom).

## 1. Sources primaires

**Parlement et textes officiels**
- `assemblee-nationale.fr`, `senat.fr`, `europarl.europa.eu` (votes et interventions)
- `legifrance.gouv.fr`, `vie-publique.fr`, `conseil-constitutionnel.fr`

**Sites des partis des candidats testés**
- Pour le test, seulement les 10 candidats des questions. **Pour le vrai site, il faudra ceux de tous les candidats** : c'est une question d'équité.

| Candidat | Parti | Site |
|---|---|---|
| Nathalie Arthaud | Lutte ouvrière | `lutte-ouvriere.org` |
| Gabriel Attal | Renaissance | `parti-renaissance.fr` |
| Raphaël Glucksmann | Place publique | `place-publique.eu` |
| Marine Le Pen | Rassemblement national | `rassemblementnational.fr` |
| David Lisnard | Nouvelle Énergie | à trouver |
| Jean-Luc Mélenchon | La France insoumise | `lafranceinsoumise.fr` |
| Édouard Philippe | Horizons | `horizonsleparti.fr` |
| Bruno Retailleau | Les Républicains | `republicains.fr` |
| Fabien Roussel | Parti communiste français | `pcf.fr` |
| Éric Zemmour | Reconquête | `parti-reconquete.fr` |

## 2. Institutions publiques et statistiques

- `insee.fr`, `ccomptes.fr` (Cour des comptes), `cor-retraites.fr` (Conseil d'orientation des retraites)
- `banque-france.fr`, `cae-eco.fr` (Conseil d'analyse économique), `strategie-plan.gouv.fr` (ex-France Stratégie)
- `drees.solidarites-sante.gouv.fr`, `immigration.interieur.gouv.fr` (statistiques de l'immigration)
- `ec.europa.eu` (Eurostat), `oecd.org` (OCDE)

## 3. Recherche académique

- `ipp.eu` (Institut des politiques publiques), `ofce.sciences-po.fr`, `sciencespo.fr`
- `cepii.fr`, `ined.fr`, `fipeco.fr` (finances publiques)
- `cairn.info`, `hal.science` (articles de recherche)

## 4. Think tanks (orientation à afficher)

Les étiquettes d'orientation seront fixées dans la charte des sources ; pour le test, l'IA doit les indiquer elle-même et on vérifie si elles sont justes.

- `institutmontaigne.org`, `fondapol.org`, `ifrap.org`, `institut-thomas-more.org`
- `jean-jaures.org`, `tnova.fr` (Terra Nova), `institut-rousseau.fr`, `fondation-copernic.org`

## 5. Vérification des faits

- `factuel.afp.com` (AFP Factuel)
- Les Décodeurs du Monde : `lemonde.fr/les-decodeurs` (à vérifier : l'outil accepte-t-il un chemin, et pas seulement un domaine ?)

## Variante à tester ensuite

Relancer les 10 questions avec une **liste de sites interdits** à la place (réseaux sociaux, vidéos, médias de divertissement), pour comparer la qualité des réponses et voir si l'IA trouve de meilleures sources quand elle cherche plus largement.
