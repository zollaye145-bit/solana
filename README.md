# Meme Sniper · Solana

Page web statique (un seul `index.html`) : swap de memecoins via Jupiter + sniper automatique, wallet Solflare.

## Checks
Liquidité ≥ $40K · Flux buys/sells · Pas de pump vertical · Mint révoquée · Freeze révoqué · Top holders · Dev % · Âge

## Sniper
Scanne les tokens Solana récents (DexScreener), applique les filtres, puis alerte ou achète automatiquement (chaque transaction est signée dans Solflare). TP / SL avec vente auto.

## Déploiement
GitHub Pages (Settings → Pages → branche `main`) ou Vercel. Aucun build.

Conseil : mets un RPC Helius/QuickNode dans les réglages, le RPC public limite vite les checks on-chain.

⚠️ Aucune clé privée n'est lue ni stockée. Memecoins = risque de tout perdre.
