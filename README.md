# Cabinet Concivium — site

Site statique (HTML/CSS/JS). Aucun build nécessaire.

## Structure
- `index.html` .......... Vitrine publique (page d'accueil)
- `app/index.html` ...... Espace client + back-office (PROTOTYPE — démo)
- `netlify.toml` ........ Config Netlify (publish racine)
- `robots.txt` .......... Empêche l'indexation de /app

## URLs une fois déployé
- Vitrine : https://VOTRE-SITE.netlify.app/
- App démo : https://VOTRE-SITE.netlify.app/app

## APIs utilisées (gratuites, sans clé)
- BOAMP (DILA / Opendatasoft) : flux des avis de marché
- Recherche d'entreprises (INSEE/Sirene) : autofill SIRET

## ⚠️ Avant la vraie mise en production
L'app (`/app`) est un prototype : pas de vrais comptes, pas de base de
données, back-office protégé côté navigateur uniquement. À brancher sur
un backend (Supabase : auth Google + email + base) avant tout usage réel.
