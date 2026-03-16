# CLAUDE.md — Instructions pour Claude Code

## Projet
Site vitrine statique Créa404 — consultant acquisition digitale, Bordeaux.

## Règles
- HTML/CSS/JS vanilla, pas de framework
- Pas de build system, pas de npm
- Fichier unique index.html + assets séparés
- Google Fonts chargé via CDN (Playfair Display + DM Sans)
- Calendly SDK chargé via CDN

## DA stricte
- Couleur accent : #5B24FF
- Titres : Playfair Display — parties violettes en italic bold 900
- Corps : DM Sans — weights 400, 500, 600, 700
- Pattern titre : `Texte noir bold` + `*accent violet italic 900*`
- Tags sections : `/ NOM` violet uppercase
- Boutons : pill (border-radius: 50px), fond violet
- Alternance fonds : blanc → gris #f4f4f4 → violet #5B24FF
- Section À propos : banner violet plein avec photo
- Section Contact : image café en fond gauche, card blanche flottante

## Ne pas toucher
- Les images dans assets/ sont les fichiers finaux
- Le logo SVG contient le chemin violet (#5B24FF) pour l'accent du 4
- L'URL Calendly est https://calendly.com/crea404/30min

## À faire
- [ ] Ajouter visuels mockup sous chaque card service (section Approche)
- [ ] Connecter formulaire à Tally.so
- [ ] Créer mentions-legales.html
- [ ] Créer politique-confidentialite.html
- [ ] Tester responsive mobile
- [ ] Optimiser images (compression webp)
- [ ] Déployer sur Netlify + pointer crea404.com via Cloudflare
