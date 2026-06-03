# Convertisseur Chiffres Arabes
**LTN LAOUAR — DPMO Dét MAINTENANCE — 8e RPIMa**

Application web PWA de conversion de chiffres occidentaux en chiffres arabes-indiens orientaux (utilisés dans les pays du Golfe, au Liban, en Égypte…).

---

## Fichiers

```
/
├── index.html      ← Application principale
├── favicon.svg     ← Icône navigateur / PWA
├── manifest.json   ← Manifeste PWA (installable sur smartphone)
├── sw.js           ← Service worker (fonctionne hors-ligne)
└── README.md
```

---

## Déploiement sur GitHub Pages

1. Créer un repo GitHub (ex: `arabic-converter`)
2. Uploader tous les fichiers à la racine
3. Aller dans **Settings → Pages**
4. Source : `Deploy from a branch` → branche `main` → dossier `/ (root)`
5. Cliquer **Save**
6. L'app sera disponible sur `https://<ton-pseudo>.github.io/arabic-converter/`

---

## Déploiement sur Vercel

### Option A — Via l'interface web
1. Aller sur [vercel.com](https://vercel.com) → **New Project**
2. Importer ton repo GitHub
3. Laisser les paramètres par défaut (pas de build nécessaire)
4. Cliquer **Deploy**
5. L'app est live sur `https://arabic-converter.vercel.app`

### Option B — Via CLI
```bash
npm i -g vercel
cd arabic-converter/
vercel
```
Suivre les instructions. Vercel détecte automatiquement le projet statique.

---

## PWA — Installation sur smartphone

- **iPhone/iPad** : Safari → icône Partage → "Sur l'écran d'accueil"
- **Android** : Chrome → menu ⋮ → "Ajouter à l'écran d'accueil"
- **PC** : Chrome/Edge → icône d'installation dans la barre d'adresse

---

## Fonctionnalités

- ✅ Conversion bidirectionnelle (Occidental ↔ Arabe)
- ✅ Pavé numérique tactile
- ✅ Copier le résultat en un clic
- ✅ Table de correspondance 0–9
- ✅ Responsive (PC, tablette, smartphone)
- ✅ Installable comme application (PWA)
- ✅ Fonctionne hors-ligne
- ✅ Identité militaire (LTN LAOUAR — DPMO — 8e RPIMa)

---

*DPMO Dét MAINTENANCE — Partenariat Militaire Opérationnel France–Liban*
