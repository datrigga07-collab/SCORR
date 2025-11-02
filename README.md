Scorr — Where the best of sports happens.

Scorr is a lightweight, single-file sports dashboard prototype (HTML + JS) that brings upcoming events across multiple sports into a focused, beautiful HUD. Follow football, basketball, F1, cycling and more — mark favourites, track countdowns, and glide through sports with swipe or keyboard navigation.

Key features (MVP):

Football: real data via API-Football (v3) — requires an API key injected via window.env.SCORR_API_FOOTBALL_KEY or Vercel env SCORR_API_FOOTBALL_KEY.

Basketball: data via balldontlie
.

Formula 1: schedule via the free Ergast API
.

Cycling: attempts public datasets; falls back to curated events (Tour de France, Giro, Vuelta) if unavailable.

Tennis, Rugby, Cricket, NFL, Hockey: curated, realistic tournament placeholders with future dates when public APIs are unavailable.

Favorites persisted in localStorage with animated star interaction.

Auto theme switching (light between 06:00–18:00; dark otherwise) with manual override.

EN/FR UI toggle (UI text only) and tasteful glassmorphic styling.

Single-file deployable (index.html), Vercel/Netlify/GitHub Pages friendly.

Scorr — Vivez tout le meilleur du sport.

Scorr réinvente la manière de vivre les événements sportifs — immédiat, élégant et pensé pour les passionnés. Classe, fluide, et ancré dans l'émotion du terrain, Scorr rassemble les meilleurs rendez-vous sportifs au même endroit : football, basket, F1, cyclisme, et plus encore.

Points clés (MVP) :

Football : données via API-Football (v3) — clé requise (injection via window.env.SCORR_API_FOOTBALL_KEY ou variable d'environnement Vercel).

Basket : données via balldontlie.

F1 : calendrier via l'API publique Ergast.

Cyclisme : tentative de récupération depuis des sources publiques ; sinon événements soignés (Tour, Giro, Vuelta).

Autres sports : placeholders réalistes et soignés pour parfaire l'expérience en attendant l'intégration d'APIs dédiées.

Favoris persistés localement, interactions animées.

Thème automatique jour/nuit (06h–18h) + bascule manuelle.

Basculement UI FR/EN, design glassmorphique élégant.

Déploiement simple : fichier unique index.html prêt pour Vercel/Netlify/GitHub Pages.
