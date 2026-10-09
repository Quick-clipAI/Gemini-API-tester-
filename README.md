# Gemini model checker

One page, no build step, no server. You paste a Gemini API key into the page while it is open; the key goes only to
`generativelanguage.googleapis.com` and is never saved or logged.

It lists the models your key can use, then tests each one you tick: a plain answer, and a answer that uses web search.
At the end it tells you which names to put in Vercel as `GEMINI_MODEL` and `GEMINI_FALLBACK_MODEL`.

## Put it online (GitHub Pages)
1. Create a new public repository, e.g. `gemini-model-checker`.
2. Upload `index.html` and this README to the repo root.
3. Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: **main** / **(root)** → Save.
4. After a minute the page is at `https://<your-username>.github.io/gemini-model-checker/`.

Never type the key into the code or commit it. Paste it only into the page.
After testing, close the tab. If you pasted the key on a shared or borrowed device, delete the key in Google AI Studio.
