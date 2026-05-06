# Open Design Fly.io Deployment

## 🚀 Deploy Steps

```bash
fly auth login
fly launch --no-deploy
fly deploy
```

## 📦 Notes
- Deploys only Next.js web (apps/web)
- Requires Node 22+
- Uses pnpm workspace

## ⚠️ Limitations
- Local agent features won't work on Fly.io
- Use API keys instead

## 🔐 Set secrets
```bash
fly secrets set OPENAI_API_KEY=your_key
```
