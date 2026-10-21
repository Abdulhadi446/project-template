---
name: deploy
description: Exact steps to deploy. Use when deploying.
---

# Deploy

Target: Vercel (default).

1. Ensure `npm run build` passes locally.
2. Commit and push to main.
3. `npx vercel --prod` (or connect repo in Vercel dashboard).
4. Set env vars in Vercel: OPENAI_API_KEY, OPENAI_BASE_URL, OPENAI_MODEL.
5. Verify deployed URL loads and core flow works.
