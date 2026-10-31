# Dorchester, Wisconsin — a town history

An illustrated history of Dorchester, Wisconsin (Clark County), from the 1873 railroad to today, built from artifacts at the Dorchester Historical Center and family photographs.

- `index.html` — the whole site (no build step)
- `img/` — photos
- `staticwebapp.config.json` — Azure Static Web Apps settings
- `.github/workflows/azure-static-web-apps.yml` — deploys to Azure on every push to `main`

## Deploying

1. Create an Azure Static Web App (Free plan). Under deployment source choose **Other**.
2. Copy its deployment token (**Manage deployment token**).
3. In this GitHub repo: **Settings → Secrets and variables → Actions → New repository secret**, name `AZURE_STATIC_WEB_APPS_API_TOKEN`, paste the token.
4. Push to `main`. The site deploys automatically; pull requests get a preview URL.
