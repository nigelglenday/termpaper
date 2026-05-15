# termpaper

A suite of TUI tools for managing Claude Code state. Sessions, transcripts, skills. From the terminal.

Landing page source for [termpaper.dev](https://termpaper.dev).

## The suite

- **[a-team](https://github.com/nigelglenday/a-team)** — parallel Claude Code session manager for Ghostty
- **[whispertty](https://github.com/nigelglenday/whispertty)** — record audio, transcribe with Whisper, label speakers
- **[skillbox](https://github.com/nigelglenday/skillbox)** — inventory and manage Claude Code skills, slash commands, subagents

All three are Python pipx installs, macOS, MIT-licensed.

## Deploy

This repo is a static one-page site. Deploys cleanly on Vercel, Cloudflare Pages, or Netlify with zero build configuration.

```bash
# Deploy to Vercel
vercel --prod
```

Custom domain: point termpaper.dev's A/CNAME at the host's records.

## License

MIT
