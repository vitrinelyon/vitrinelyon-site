# Vitrine Lyon — site

Site vitrine de l'activité. HTML statique, aucune dépendance, aucun build.

- `index.html` : la page (refonte motion du 2026-11-04, GSAP via cdnjs) ; `v2/` : page du 2026-10-20 archivée, non indexée ; `v1/` : première page archivée, non indexée ; `demos/exemple-garage/` : exemple fictif intégré à la page
- `_redirects` : `/v3/` (ancienne adresse de la page actuelle) renvoie vers `/`
- `mentions-legales.html` : mentions légales (SIREN 131 685 026, RCS Lyon)
- `_headers` : en-têtes de sécurité pour Cloudflare Pages

Déployé sur Cloudflare Pages depuis la branche `main`. Chaque push met le site à jour.

Formulaire : Web3Forms, clé configurée dans `index.html` (compte contact.vitrinelyon@gmail.com).
