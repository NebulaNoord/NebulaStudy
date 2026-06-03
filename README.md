# NebulaStudy

## Local development

Start a lightweight local server to preview the site:

```bash
python3 -m http.server 3000
# then open http://localhost:3000
```

Alternatively, if you use npm scripts:

```bash
npm run dev
```

## Deploying to Vercel

This project is a static site. Vercel will serve `index.html` directly. You can deploy either by connecting the repository in the Vercel dashboard or using the Vercel CLI:

```bash
# install Vercel CLI
npm i -g vercel
# deploy
vercel
```

The repository includes `vercel.json` to ensure the static builder is used.
