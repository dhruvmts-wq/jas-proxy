# jas-proxy

Vercel serverless proxy for the [Job Application Suite](https://github.com/dhruvmts-wq/job-application-suite).

Forwards requests from the GitHub Pages tool to the Anthropic API, keeping the API key secure on the server side.

## Setup

1. Import this repo into [Vercel](https://vercel.com)
2. Add environment variable: `ANTHROPIC_API_KEY` = your `sk-ant-...` key
3. Deploy — your proxy URL will be `https://<your-project>.vercel.app/api/claude`
4. Paste that URL into the Job Application Suite tool
