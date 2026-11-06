# Slides

Présentations HTML, consultables en ligne via GitHub Pages.

| Présentation | Lien | Fichier |
|---|---|---|
| **Le MCP expliqué avec un annuaire téléphonique** : ce qu'est un MCP, illustré par des petits films en stop-motion (avec musique) | [Ouvrir](https://pikooli.github.io/slide/content/mcp.html) | [`content/mcp.html`](content/mcp.html) |
| **La FAQ propulsée par Notion** (Hiway) : comment la FAQ passe de Notion à l'app | [Ouvrir](https://pikooli.github.io/slide/content/notion-support.html) | [`content/notion-support.html`](content/notion-support.html) |

Page d'accueil avec la liste des présentations : <https://pikooli.github.io/slide/> ([`index.html`](index.html)).

## Naviguer dans une présentation

- **← / →** ou **Espace** : slide précédente / suivante
- **F** : plein écran (présentation MCP)
- **M** : couper / remettre la musique (présentation MCP)

## Ajouter une présentation

1. Déposer le fichier `.html` dans `content/`.
2. Ajouter une ligne dans le tableau ci-dessus, avec le lien `https://pikooli.github.io/slide/content/<fichier>.html`, et une carte dans `index.html`.
3. Commit et push sur `main` : GitHub Pages se met à jour en une ou deux minutes.

## Activer GitHub Pages (une seule fois)

Sur GitHub : **Settings → Pages → Build and deployment**, choisir *Deploy from a branch*, branche `main`, dossier `/ (root)`.

Chaque fichier est autonome (un seul `.html`, sans build) : on peut aussi l'ouvrir directement en local dans un navigateur.
