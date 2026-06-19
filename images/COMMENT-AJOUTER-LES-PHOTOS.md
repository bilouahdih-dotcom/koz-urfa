# 📸 Remplacer les photos d'illustration par les vraies

Le site contient actuellement des **photos d'illustration libres de droits** (temporaires).
Pour mettre les **vraies photos du restaurant**, remplace simplement les fichiers de ce dossier
en **gardant exactement le même nom**. La photo s'affiche alors automatiquement au bon endroit.

## Fichiers utilisés par le site

| Fichier à remplacer | Où il apparaît |
|---|---|
| `grillades.jpg` | Fond de la bannière d'accueil + case « Brochettes au köz » |
| `assiette.jpg`  | Bloc « Notre histoire » + case « Assiette » |
| `salle.jpg`     | Case « Salle du restaurant » |
| `sandwich.jpg`  | Case « Sandwich kebab » |
| `dessert.jpg`   | Case « Baklava » |
| `burger.jpg`    | Case « Burger maison » |
| `the.jpg`       | Case « Thé turc » |

> 💡 Idéalement une photo de **devanture** du restaurant : ajoute `devanture.jpg` ici et dis-le moi,
> je l'intègre (par ex. en grande case à la place du burger).

## Conseils
- Formats : `.jpg` (ou `.png`, mais garde l'extension `.jpg` dans le nom, ou préviens-moi).
- Photos nettes, plutôt horizontales, au moins 1000 px de large.
- ⚠️ N'utilise que des photos dont tu as le droit : celles prises au restaurant ou fournies par le client.
  Les photos d'illustration actuelles viennent d'Unsplash (libres de droits) et sont à remplacer
  avant une mise en ligne définitive « au nom du restaurant ».

## Publier après remplacement
```
git add .
git commit -m "Vraies photos du restaurant"
git push
```
Le site en ligne se met à jour tout seul.
