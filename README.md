# GPT ASTRA

A minimal, mobile-friendly chat workspace with a provider switch for OpenAI and Anthropic Claude.

## Run locally
1. Install Node.js 20+.
2. In this folder, run `npm install`.
3. Copy `.env.example` to `.env.local`.
4. Add your API keys to `.env.local`:
   - `OPENAI_API_KEY=...`
   - `ANTHROPIC_API_KEY=...`
5. Run `npm run dev` and open http://localhost:3000.

## Deploy
Deploy this Next.js project to a Node-compatible host such as Vercel. Add the two keys in the host's **server-side environment variables** before deploying. Never put API keys in browser code, commit them, or use `NEXT_PUBLIC_` for them.

## Important
- This is source code, not a live hosted website yet.
- Actual provider replies require valid API keys and provider billing/access.
- API calls are server-side; don't expose secret keys to visitors.
- For a public launch, add authentication, rate limiting, abuse protection, and usage limits before sharing widely.
