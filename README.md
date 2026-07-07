# 🏗️ Auction Flipper — Staging Environment

This is the **staging** deployment for [Auction Flipper](https://github.com/binhusmachado-code/auction-flipper).

## 🌐 Live URLs

| Environment | URL | Branch |
|---|---|---|
| **Production** | https://binhusmachado-code.github.io/auction-flipper/ | `main` |
| **Staging** | https://binhusmachado-code.github.io/auction-flipper-staging/ | `staging` |

## 🔄 How It Works

- The `staging` branch in the main repo is auto-synced to this repo every 15 minutes
- Any push to the `staging` branch triggers an immediate re-deploy
- Use staging to test changes before merging to `main`

## 🚀 Workflow

1. Create a feature branch from `staging`
2. Push changes to the `staging` branch in the main repo
3. Wait ~2 minutes for auto-deploy to https://binhusmachado-code.github.io/auction-flipper-staging/
4. Test on staging
5. Merge `staging` → `main` for production deploy
