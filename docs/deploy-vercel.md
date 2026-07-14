# Deploy to Vercel

This repo serves the **static design preview** from the `preview/` folder.

## Dashboard (recommended)

1. Push this repo to GitHub.
2. Vercel → **Add New Project** → import the repo.
3. Confirm settings (already set in root [`vercel.json`](../vercel.json)):
   - Framework: Other / none  
   - Build Command: empty  
   - Output Directory: `preview`
4. Deploy.

## CLI

From the repo root (with [Vercel CLI](https://vercel.com/docs/cli) installed):

```bash
npx vercel login
npx vercel
```

Production:

```bash
npx vercel --prod
```

## After deploy

- Share the `*.vercel.app` URL with the client.
- Optional: Project → **Settings** → **Domains** to attach a custom domain.
