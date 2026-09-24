# ariane-starter-kit

Point de départ pour styliser [Ariane](https://github.com/jogo-labs/ariane) : un thème CSS neutre (`ariane-starter.css` + `ariane-starter/`) à copier/forker, et une démo statique de tous les composants avec ce thème.

## Démo

👉 [Voir la Kitchen Sink](https://jogo-labs.github.io/ariane-starter-kit/)

## Utilisation

Copiez `ariane-starter.css` et le dossier `ariane-starter/` dans votre projet et adaptez les fragments à votre identité visuelle :

```html
<script type="module" src="https://unpkg.com/@ariane-ui/core/cdn/autoloader.prod.js"></script>
<link rel="stylesheet" href="./ariane-starter.css" />
```

`ariane-starter.css` est une liste d'imports vers `ariane-starter/` (palette, tokens sémantiques, tokens globaux, tokens partagés, un fragment par composant) — supprimez ou remplacez un fragment que vous ne gardez pas, ou ajoutez le vôtre en l'important à votre tour.

## Régénérer

`index.html`, `ariane-starter.css` et `ariane-starter/` sont générés depuis le monorepo [`ariane`](https://github.com/jogo-labs/ariane) — ne pas les éditer à la main ici. Voir `docs/superpowers/specs/2026-09-23-starter-kit-demo-230-design.md` dans ce repo-là pour le flux complet.
