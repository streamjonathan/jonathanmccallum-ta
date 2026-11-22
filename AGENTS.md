# AGENTS.md — jonathanmccallum-ta (Tamil mirror of jonathanmccallum.com)

Tamil mirror site. Same theme and design as the main site (Paper Light),
content translated into Tamil, meaning-first. Repo: streamjonathan/jonathanmccallum-ta.
Live (when approved): ta.jonathanmccallum.com. Proof: jonathanmccallum-ta.pages.dev.

## Mission

Mirror jonathanmccallum.com in Tamil — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Tamil site goes live on ta.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: respectful plain Tamil, reader addressed as "நீங்கள்". Short plain
  sentences, warm and honest, no preaching. Scene → reflection → question.
- Names (never vary): இயேசு, அஸ்லான், நார்னியா, லூசி, டிகோரி, டிரியன்,
  ஆதாம், ஏவாள் (standard Tamil Bible names), லூயிஸ் / சி. எஸ். லூயிஸ்.
  Book titles are meaning-first — NO published Tamil titles were found (web
  search, 22 Nov 2026), flagged for Jonathan: நார்னியா கதைகள்,
  மந்திரவாதியின் மருமகன், பெரும் விவாகரத்து, விண்வெளி முத்தொகுப்பு,
  இறுதிப் போர்.
- Bible verses: no direct verse quotations appear in these 5 articles —
  paraphrase only, never quoted as Scripture. No direct Lewis quotations either.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
