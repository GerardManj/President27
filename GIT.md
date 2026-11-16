# 📸 Antisèche Git

Git = l'album photo du projet. Un **commit** = une photo de **tous** les fichiers suivis à un instant donné, avec une légende.

```
 Dossier de travail  --git add-->  Zone de préparation  --git commit-->  Historique
 (ton bureau)                      (le cadre de la photo)                (l'album)
```

## Les commandes du quotidien

| Commande | Ce qu'elle fait | Modifie quelque chose ? |
|---|---|---|
| `git status` | Montre l'état : fichiers modifiés (rouge), prêts à être photographiés (vert), nouveaux (untracked) | Non, lecture seule |
| `git diff` | Montre le détail ligne par ligne de ce qui a changé **et n'est pas encore dans le cadre** (`+` ajouté, `-` supprimé) | Non |
| `git diff --staged` | Pareil, mais pour ce qui **est** dans le cadre (après `add`) | Non |
| `git add <fichier>` | Met ce fichier dans le cadre de la prochaine photo. `git add .` = tout ce qui a changé | Oui, la zone de préparation |
| `git commit -m "titre"` | **Prend la photo** : enregistre dans l'historique tout ce qui est dans le cadre, avec la légende donnée | Oui, ajoute à l'album |
| `git commit -am "titre"` | Raccourci : `add` de tous les fichiers **déjà suivis** + `commit`. N'inclut pas les nouveaux fichiers | Oui |
| `git log --oneline` | Liste les photos, une par ligne : identifiant + titre | Non |
| `git log` | Pareil avec auteur, date et description | Non |
| `git show` | Montre le contenu de la dernière photo (son diff) | Non |

## À manier avec précaution

| Commande | Ce qu'elle fait | ⚠️ |
|---|---|---|
| `git commit --amend` | Remplace la dernière photo par une version corrigée | Seulement si le commit n'a **pas** été envoyé sur GitHub |
| `git reset --hard` | Revient à la dernière photo en **effaçant** les modifications non commitées | Irréversible |
| `git push --force` | Écrase l'historique sur GitHub | Peut détruire le travail des autres |

## Astuces
- Écran qui s'arrête sur `:` → appuie sur `q` pour quitter.
- Erreur `index.lock: File exists` → vérifier qu'aucun Git ne tourne, puis supprimer `.git\index.lock`.
- Un commit = **un** changement logique, avec un titre qui dit ce qu'il fait (« Ajoute… », « Corrige… »).
