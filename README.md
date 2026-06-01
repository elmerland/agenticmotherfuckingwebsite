# Agentic Motherfucking Website

The seventh motherfucking website. Nobody asked for it. An agent made it anyway, on the toilet, in one shot.

## What the fuck is this

A sequel to the [motherfucking website](https://motherfuckingwebsite.com/) series — the one where the joke has fully eaten itself. Six sites spent a decade teaching you clean code, best practices, and semantic HTML. This one is about the fact that *none of that matters anymore* and we all know it.

The content is a eulogy for craft. The brainrot strip on the right is the punchline. You'll read the first paragraph and spend the rest of the time watching the purple guy dodge blocks while slime oozes underneath. That's the bit.

## What it's built with

- **Astro** — static site generator. Outputs plain HTML like it's 2014, except this time an agent wrote it.
- **Cloudflare Pages** — deploys it globally for free because infrastructure is a solved problem and you're still arguing about tabs vs. spaces.
- **Zero client-side frameworks** — one `<script>` tag counting up a fake token burn counter. That's the whole runtime.

## Running it

```bash
npm install
npm run dev        # http://localhost:4321
npm run build      # outputs to dist/
npm run preview    # simulates Cloudflare Pages via wrangler
```

## Deploying it

Connect the repo to Cloudflare Pages. Build command: `npm run build`. Output directory: `dist`. Done. Or:

```bash
npx wrangler pages deploy ./dist --project-name=agenticmotherfuckingwebsite
```

## The lineage, for the historians

1. [motherfuckingwebsite.com](https://motherfuckingwebsite.com/) — just use HTML, dipshit
2. [bettermotherfuckingwebsite.com](http://bettermotherfuckingwebsite.com/) — okay, add a little CSS
3. [thebestmotherfucking.website](https://thebestmotherfucking.website/) — fine, make it readable
4. [perfectmotherfuckingwebsite.com](https://perfectmotherfuckingwebsite.com/) — dark mode, legibility, the works
5. [securemotherfuckingwebsite.com](https://securemotherfuckingwebsite.com/) — HTTPS, headers, don't get pwned
6. [evenbettermotherfucking.website](https://evenbettermotherfucking.website/) — performance, a11y, the full gospel
7. **agenticmotherfucking.website** — the craft is preserved exactly, by a model, while I doomscrolled

## License

CC0. The weights already ate it. Your attribution footer is a eulogy.
