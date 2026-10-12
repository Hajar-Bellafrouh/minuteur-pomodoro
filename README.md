# ⏰ Pomodoro Timer

Minuteur Pomodoro en HTML, CSS et JavaScript (sans dépendance), avec une liste de tâches.

## Fonctionnalités

- Trois minuteurs : **Pomodoro** (25 min), **Pause courte** (5 min) et **Pause longue** (10 min)
- Boutons **START**, **STOP** et **RESET**
- Alarme sonore à la fin du minuteur
- Liste de tâches : ajout et suppression (non conservée au rechargement de la page)
- Affichage adapté aux petits écrans

## Utilisation

Ouvrir `index.html` dans un navigateur : aucune installation n'est nécessaire.

Pour un serveur local :

```bash
python -m http.server 8000      # puis http://localhost:8000
```

## Structure

```
pomodoro-timer/
├── index.html
├── css/style.css
├── js/script.js
└── assets/
    ├── images/montagne.jpg            Image de fond
    └── sounds/notification-sons.wav   Alarme de fin
```

## Publier sur GitHub Pages

Après le `push` : **Settings → Pages → Source : Deploy from a branch → `main` / `(root)`**.
Le site sera disponible à l'adresse `https://VOTRE-NOM.github.io/pomodoro-timer/`.

## Personnaliser les durées

Les durées (en minutes) sont définies dans `index.html`, via l'attribut `data-duration` de chaque minuteur
(`pomodoro-timer`, `short-timer`, `long-timer`). Les valeurs doivent être des nombres entiers.

## Crédits et licences

- Police : [Poppins](https://fonts.google.com/specimen/Poppins) (Google Fonts, chargée en ligne).
- Image de fond et son d'alarme : *source à compléter*. Le code référençait à l'origine un fichier nommé
  `mixkit-happy-bells-notification-937.wav`, ce qui suggère un son [Mixkit](https://mixkit.co/). Vérifiez les licences
  de l'image et du son avant de publier le dépôt.
