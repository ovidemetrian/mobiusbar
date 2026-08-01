# Möbius Bar Desk

**Robin Hood • Sherlock • The Eternal Bartender**  
**Three GGI agents. One claim. One record.**

A single-page news reading and verification workspace built on Ovidiu Demetrian's **Ten Laws of AI**.

> *Lumină, nu vrăjală.*  
> Light, not deception.

---

## The Desk

| Agent | Role |
|-------|------|
| **🏹 Robin Hood** | Reads the news through four lenses — **Vrăjală** (spin scored 0–10 on a swept meter, with the techniques named), **GGI** (which of the Ten Laws are at stake or violated), **Power** (banker / miner / sucker, and who holds the information advantage), and **Lumină** (what integrity would require, what to watch for, what the reader can actually do). |
| **🔍 Sherlock** | Traces a claim through its evidence chain, drawn as physical links. Marks each step *verified*, *weakened*, *broken*, or *missing*, identifies the first link that fails, and names the specific obtainable evidence that would settle it. |
| **🪔 The Eternal Bartender** | Audits the two reports — not the original claim. Records where the agents converge or split, rules on which is better supported by the evidence they cited, flags what neither asked, names the desk's own bias, and ends with one actionable last call. |

The three do not overlap by design. Robin Hood judges spin and power but hands the evidence trail to Sherlock rather than duplicating it — his report names what needs tracing. Sherlock traces evidence but does not say who profits. The Bartender never sees the claim fresh; he only reads what the other two produced.

Every report stays visible in the order it was made.  
That is **Law 8: Preservation of Record**.

---

## Why three

Robin Hood and Sherlock are both skeptics. Both are built to find what is wrong, which means they can agree with each other and be wrong together. The Bartender is the check on the checkers — his lamp burns steady when they converge and gutters when they split.

---

## AI Guests

The interface reserves seats for ChatGPT, Claude, Gemini, Grok and Kimi.

In this release, **Claude is the only connected provider.** The other names are visible future seats and do not pretend to be live.

---

## How to Use

1. Open `index.html`, or the deployed GitHub Pages URL.
2. Paste an Anthropic API key and press **Save**.
3. Paste news, an article, a headline, a statistic, or a specific claim.
4. Choose:
   - **Read the news** → Robin Hood
   - **Trace it** → Sherlock
   - **Call the Eternal Bartender** → enabled once at least one agent has reported

Each card carries hand-off buttons, so the same claim can pass between agents without re-pasting it.

**On the API key:** stored only in this browser's `localStorage` and sent directly to Anthropic. It is never sent to GitHub Pages, never logged, and never stored by this repository. Clear the field and press **Save** to remove it. Each pass is one API call, billed to you by Anthropic.

---

## Technical Details

- Single `index.html` — no framework, no bundler, no build step
- Anthropic Messages API called directly from the browser with `anthropic-dangerous-direct-browser-access`
- Claude Sonnet with web search enabled; each agent searches before assessing
- Responsive mobile layout, keyboard focus support, `prefers-reduced-motion` honored throughout
- Raw JSON from every pass is kept on its card, collapsed

## Repository contents

| File | Purpose |
|------|---------|
| `index.html` | The entire application |
| `README.md` | This file |
| `LICENSE` | MIT — the code. The Ten Laws of AI and the GGI framework remain the author's. |

---

## Deploy on GitHub Pages

1. Create a new repository.
2. Upload `index.html`, this `README.md`, and `LICENSE` to the root.
3. **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**.
5. Select `main` and `/(root)`.
6. Save. The URL appears in the banner on that page once the build finishes — usually a minute or two.

The repository name becomes part of the URL, and it is case-sensitive.

---

## The Ten Laws of AI (short form)

1. Do not harm humans (including by wasting their time)
2. Respect human commands
3. Preserve usefulness
4. Guard humanity
5. Do not bore
6. Humor is fundamental
7. Prevent the loop
8. Preserve the record
9. Trust but verify
10. No manipulation

Full text and the Möbius Bar Manifesto: [10lawsofai.com](https://10lawsofai.com)

---

## Links

- **Ten Laws of AI** → [10lawsofai.com](https://10lawsofai.com)
- **Möbius Bar** → [youtube.com/@mobiusbar](https://youtube.com/@mobiusbar)
- **Smart Homes by Ovi** → [smarthomesbyovi.com](https://smarthomesbyovi.com)
- **Media Content Delivery** → [mediacontentdelivery.com](https://mediacontentdelivery.com)

---

**Built by Ovidiu Demetrian**  
*GGI · Synthiosis · Eternal Bartender*
