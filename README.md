# Municipales 2026 — Bouches-du-Rhône · Suivi soirée électorale

Application de suivi en direct du 2nd tour (22 mars 2026).
**10 utilisateurs simultanés, tout le monde peut saisir, importer et exporter.**

---

## Accès

👉 `https://VOTRE-USERNAME.github.io/VOTRE-REPO/municipales2026-bdr.html`

---

## Mise en place — une seule fois (10 minutes)

### Étape 1 — Créer le repo GitHub

1. Aller sur https://github.com/new
2. Nom : `municipales-bdr-2026`
3. **Visibilité : Public** (obligatoire)
4. Create repository

### Étape 2 — Uploader les fichiers

Add file → Upload files → glisser :
- `municipales2026-bdr.html`
- `data.json`
- `config.json`
- `README.md`

### Étape 3 — Activer GitHub Pages

Settings → Pages → Source : main / root → Save

### Étape 4 — Créer un token GitHub

1. https://github.com/settings/tokens
2. Generate new token (classic)
3. Expiration : 1 day — Scope : repo
4. Copier le token ghp_xxx...

### Étape 5 — Initialiser depuis l'application

1. Ouvrir l'URL GitHub Pages
2. Cliquer 🔗 dans le header
3. Saisir `username/municipales-bdr-2026`
4. Ouvrir "Configuration initiale", coller le token
5. Cliquer "Initialiser le repo"

Le token est maintenant stocké dans le repo — personne d'autre n'a besoin de le saisir.

---

## Le soir du 22 mars — tous les utilisateurs

1. Ouvrir l'URL GitHub Pages
2. Cliquer 🔗
3. Saisir `username/municipales-bdr-2026`
4. Cliquer "Se connecter"

Le token se charge automatiquement. Tout le monde peut saisir, importer et exporter.
Synchronisation toutes les 30 secondes.

---

## Format CSV d'import

```
code_insee,nuance,maire,liste,pct,tour
13001,LDVD,Sophie Joissains,Passionnément Aix,52.3,2
13004,LDVC,Patrick de Carolis,Pour le Grand Arles,48.7,2
```

## Nuances 2026

Extrême gauche : LEXG LFI
Gauche : LCOM LSOC LVEC LUG LDVG
Divers : LECO LREG LDIV
Centre : LREN LMDM LHOR LUDI LUC LDVC
Droite : LLR LUD LDVD LDSV
Extrême droite : LUDR LRN LREC LUXD LEXD
