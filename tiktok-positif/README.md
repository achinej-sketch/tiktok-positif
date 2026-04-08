# Média Positif TikTok

Application web complète pour trouver les bonnes nouvelles du jour et générer des scripts TikTok avec Claude IA.

## Déploiement sur Vercel (5 minutes)

### Étape 1 — Compte Vercel
Crée un compte gratuit sur https://vercel.com (connexion avec GitHub recommandée)

### Étape 2 — Déploiement
1. Va sur https://vercel.com/new
2. Clique "Browse" ou glisse-dépose le dossier `tiktok-positif`
3. Vercel détecte automatiquement la config
4. Clique "Deploy"
5. En 1-2 minutes, ton app est en ligne avec une URL du type `tiktok-positif.vercel.app`

### Étape 3 — Utilisation
1. Ouvre ton URL Vercel
2. Entre ta clé API Anthropic (https://console.anthropic.com)
3. Choisis une thématique et lance la recherche
4. Génère tes scripts TikTok !

## Structure du projet

```
tiktok-positif/
├── vercel.json          # Config Vercel
├── api/
│   └── claude.js        # Proxy vers l'API Anthropic (résout le CORS)
└── public/
    └── index.html       # Interface complète
```

## Coût estimé
- Vercel : gratuit (plan hobby)
- Claude API : ~0.02€ par recherche complète (5 news + 5 scripts)
- Budget mensuel estimé : 5-15€ pour une utilisation quotidienne

## Fonctionnalités
- Recherche web automatique des bonnes nouvelles du jour
- Scoring IA de positivité (0-10)
- Génération de scripts TikTok optimisés (hook, développement, CTA, hashtags)
- Copie en un clic
- Régénération de script si besoin
