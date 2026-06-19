# 📸 Comment ajouter les vraies photos

Dépose tes images **dans ce dossier `images/`** en les nommant **exactement** comme ci-dessous.
Dès qu'un fichier est présent avec le bon nom, il s'affiche tout seul dans la galerie du site.
Si un fichier manque, l'icône de secours reste affichée (pas de bug).

## Noms de fichiers attendus

| Fichier à déposer | Emplacement sur le site |
|---|---|
| `devanture.jpg` | La devanture du restaurant (grande case) |
| `salle.jpg`     | L'intérieur / la salle (grande case) |
| `grillades.jpg` | Les brochettes / grillades au köz (grande case verticale) |
| `sandwich.jpg`  | Un sandwich kebab |
| `assiette.jpg`  | Une assiette garnie |
| `dessert.jpg`   | Un dessert (baklava, künefe…) |
| `the.jpg`       | Le thé turc / une boisson |

## Astuces

- Formats acceptés : `.jpg` ou `.png` (si tu utilises `.png`, change l'extension dans `index.html`, ou renomme simplement ton fichier en `.jpg`).
- Idéalement des photos **horizontales** et nettes, au moins 1000 px de large.
- ⚠️ N'utilise que des photos dont tu as le droit (celles du restaurant, ou prises par toi). Les photos Instagram appartiennent au restaurant : à utiliser une fois le client d'accord.

## Pour publier après ajout

Dans le terminal :
```
git add .
git commit -m "Ajout des vraies photos"
git push
```
Le site en ligne se met à jour tout seul.
