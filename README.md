# Awesome Product-URL → UGC Ad Scripts

A curated list of tools that turn a **product page / Shopify URL** into **hooks, scripts, or ads you can actually ship**.

This is not a “cheapest AI video” directory. Entries are grouped by **what they deliver**. Differences are spelled out. Prices below are **public list prices we last checked in 2026** — treat them as directional, not a quote.

**Maintained by [Hookly](https://hookly.cc)** (`hookly.cc`). Hookly is listed in the same table as everyone else. No paid placements. No fake testimonials.

## How to read this

| Label | Meaning |
| --- | --- |
| **Scripts / packs** | Text you can film: hook, VO, captions, shots. You (or a creator) shoot it. |
| **Rendered video** | The tool outputs a video (avatar, stock, product 3D). |
| **Swipe file** | Other brands’ hooks. You rewrite. |
| **Verified** | We used the product or its public docs. |
| **From marketing** | Taken from the vendor site; not independently timed. |

Method: public pricing pages + our own use of Hookly. We do **not** invent review quotes.

---

## Scripts you can film (our category)

Tools whose main output is **words + shot list**, not a rendered clip.

| Tool | Input | Output | Price (public, 2026) | Notes |
| --- | --- | --- | --- | --- |
| [Hookly](https://hookly.cc) | Product URL | 5 filmable 9:16 packs (hook, VO, captions, CTA, shots) + [teleprompter](https://hookly.cc/p/demo) | $29 / $79 / $199 mo | Also [HTTP API](https://hookly.cc/api), [MCP](https://hookly.cc/mcp), CLI, Chrome extension. Templates / Workers AI — not a paid video model. **We make this product.** |
| [HookMafia](https://www.hookmafia.com) | Browse library | Other people’s hooks | From marketing | Swipe file. Fast for reference; not tied to *your* SKU. |

**Honest difference:** a swipe file is research. A pack is something you can shoot tonight. Hookly is priced for the pack, not to undercut a list of lines.

---

## AI video / avatar suites

| [Ideoy](https://ideoy.ai) | Remake this week's viral meme videos from one selfie (MiniMax H3, 9:16) | Freemium | — |
These **render** a clip. Useful if you want a file without a creator. Different job than a filmable script.

| Tool | Input | Output | Price (public, 2026) | Notes |
| --- | --- | --- | --- | --- |
| [Topview](https://www.topview.ai) | URL / assets | AI product video, avatars | Typically ~$39–$99+ seats (from marketing) | Studio. You wait on a render. |
| [HeyGen](https://www.heygen.com) | Script + avatar | Talking-head video | From marketing (tiered) | Avatars. Cheap to ignore if the first line is weak. |
| [Creatify](https://creatify.ai) | Product URL | AI product videos | From marketing | URL-in is similar; output is a render, not a phone shot list. |
| [LightReel](https://www.lightreel.ai) | Product / brief | AI reels | From marketing | Reel studio, not a teleprompter pack. |

**Honest difference:** rendered video is convenient and often looks synthetic on Meta/TikTok. A filmable pack is uglier on day one and more native if someone actually shoots it.

---

## Adjacent (not the same job)

| Tool | Why it’s adjacent |
| --- | --- |
| [AdCreative.ai](https://www.adcreative.ai) | Display / static ad volume, not 9:16 UGC scripts. |
| [Pictory](https://pictory.ai) / [InVideo](https://invideo.io) | Long-form / stock editors. |
| [Captions](https://www.captions.ai) | Mobile editor + AI host. You still need the hook. |

---

## Agent / machine access

If a bot should paste a URL and get JSON, without a browser:

- **Hookly** — `POST https://hookly.cc/api/generate` `{"url":"…"}` · contract `GET /api` · MCP `POST /mcp` (`generate_packs`, `get_pack`, `list_public`) · CLI `node hookly.mjs generate <url>`
- Most video suites above are **web-only** as of 2026 (from marketing). File an issue if that’s wrong.

---

## E-E-A-T rules for this list

1. **Experience** — examples are labeled. Hookly demo: https://hookly.cc/p/demo (sample pack, not a customer quote).
2. **Expertise** — we describe *jobs* (script vs render vs swipe), not vibes.
3. **Authoritativeness** — competitors stay on the list. We do not delete them to “win.”
4. **Trust** — no invented testimonials, no fake “as seen in,” no stealth affiliates unless marked.

Quality and UX beat a race to $9. Price can follow delivery. Do not lose money on model COGS to look cheap.

---

## Contribute

PRs welcome. Add a tool only with: URL, job (script / render / swipe), public price source, and one honest limitation.

License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
