# Créa404 — Site principal

Site vitrine statique pour Créa404, consultant en acquisition digitale (Bordeaux).

## Stack
- HTML / CSS / JS statique
- Hébergé sur Netlify
- DNS via Cloudflare
- Domaine : crea404.com

## Structure
```
crea404/
├── index.html          # Page d'accueil (one-page)
├── assets/
│   ├── logo.svg        # Logo Créa404 horizontal noir
│   ├── anthony.webp    # Photo Anthony (section À propos)
│   ├── contact-bg.webp # Photo fond section Contact
│   └── logos/          # Logos clients (bandeau confiance)
│       ├── alt.webp
│       ├── aston-vapote.webp
│       ├── chez-ernest.webp
│       ├── el-diablo.webp
│       ├── entreprise-gaube.webp
│       ├── jet-boat-school.webp
│       ├── terrasse-vigean.webp
│       └── vins-temps.webp
├── mentions-legales.html       # À créer
├── politique-confidentialite.html  # À créer
└── README.md
```

## Design system
- **Accent** : #5B24FF (violet)
- **Typo titres** : Playfair Display (serif) — italique bold 900 pour accents violets
- **Typo corps** : DM Sans (sans-serif)
- **Boutons** : border-radius 50px (pill), fond violet
- **Pattern titres** : Noir bold + *italique violet Playfair 900*
- **Tags sections** : `/ NOM` — violet uppercase 14px
- **Sections** : alternance blanc / gris clair (#f4f4f4) / violet (#5B24FF)

## Sections (ordre de scroll)
1. Hero — H1 + sous-titre + 2 CTA
2. Bandeau logos — Carousel défilant infini
3. Approche — 3 leviers (référencement local, pub en ligne, pages de vente)
4. À propos — Banner violet plein + photo Anthony
5. Méthode — 4 étapes (audit, stratégie, activation, suivi)
6. CTA Banner — Violet, prise de RDV Calendly
7. Contact — Image fond + card info + formulaire
8. Footer

## Formulaire
- Actuellement : alert() placeholder
- À connecter : Tally.so → Google Sheets

## Calendly
- URL : https://calendly.com/crea404/30min
- Widget popup intégré via SDK

## Sous-domaine BTP
- offre-btp.crea404.com → projet séparé, pas dans ce repo
- Juste un déplacement de domaine, contenu existant inchangé

## Déploiement
```bash
# Netlify CLI
netlify deploy --prod --dir=.
```
