# Extension catalogue Fast Cars Dubai

Ce repository contient les **nouveaux véhicules** du catalogue Fast Cars Dubai (extension du site principal).

## Contenu

- `vehicles.json` — métadonnées des nouveaux véhicules
- `cars/<Brand>/<Model>/` — images associées à chaque véhicule

## Images

- `1.*` = cover principale
- `2.*`, `3.*`, … = galerie
- Noms d’images purement numériques (`1.jpeg`, `2.jpeg`, …)

Le slug JSON correspond au dossier, en minuscules :

`cars/Lamborghini/Huracan-Evo-Spyder/` → `"slug": "lamborghini/huracan-evo-spyder"`

## IDs

Les IDs de ce repository commencent à **241**.

Le repository principal du site conserve les **240 véhicules historiques** (IDs 1–240).
