# L'IA, c'est aussi puissant que le contexte qu'on lui donne

Présentation Reveal.js pour un atelier Lunch & Learn — destinée aux développeurs, designers et chefs de projet.

## Voir la présentation

Ouvrir `index.html` directement dans un navigateur, ou servir le dossier localement:

```bash
npx serve .
# puis ouvrir http://localhost:3000
```

La présentation est également publiée via GitHub Pages sur la branche `main`.

## Contenu

18 diapositives organisées en 6 phases:

| Phase | Sujet |
|-------|-------|
| 1 | Le constat — pourquoi l'IA répond à côté sans contexte |
| 2 | Définition du contexte et hiérarchie |
| 3 | Exemple concret: le système `/docs` d'AllDressed |
| 4 | Les 5 principes, déclinés par rôle (dev, design, PM) |
| 5 | Vision au-delà du code — CRM alimenté par l'IA |
| 6 | Résumé et discussion |

## Stack

- [Reveal.js 5](https://revealjs.com/) via CDN — aucun build nécessaire
- CSS custom (`css/theme.css`) — thème clair, police Inter, accent indigo
- Compatible GitHub Pages (fichiers statiques, pas de serveur requis)

## Structure

```
ai-context-presentation/
├── index.html       # Toutes les diapositives
├── css/
│   └── theme.css    # Thème personnalisé Reveal.js
├── assets/
│   └── img/         # Captures d'écran et diagrammes (optionnel)
└── README.md
```

## Navigation

| Action | Raccourci |
|--------|-----------|
| Diapositive suivante | `→` ou `Space` |
| Diapositive précédente | `←` |
| Vue d'ensemble | `Esc` |
| Plein écran | `F` |
| Notes présentateur | `S` |

## GitHub Pages

Pour activer GitHub Pages:

1. Aller dans **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main`, dossier: `/ (root)`
4. Sauvegarder — la présentation sera disponible sur `https://<user>.github.io/<repo>/`
