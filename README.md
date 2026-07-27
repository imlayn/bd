# Alif & Amira Im — voyage d'étoile en étoile

Lecteur de BD à pages : les dialogues sont directement intégrés dans
chaque illustration (bulles de BD), navigation à la flèche.

## Fichiers (tous à la racine, à uploader ensemble)

```
index.html
style.css
app.js
pages.json
page-1.svg … page-10.svg
```

## Publier sur GitHub Pages

1. Dépose tous ces fichiers **à plat, à la racine** du dépôt (pas dans
   un sous-dossier).
2. Settings → Pages → Source : branche `main`, dossier `/ (root)`.
3. Le site est en ligne à `https://<utilisateur>.github.io/<repo>/`.

## Ajouter une page

1. Ajoute `page-11.svg` (ou autre format) dans le dossier.
2. Ajoute une entrée dans `pages.json` :
   ```json
   { "id": 11, "image": "page-11.svg" }
   ```

## Navigation

- Flèches ← / → sous l'image
- Flèches du clavier
- Swipe sur mobile
- Points de progression cliquables
