# 🍸 The Möbius Bar
**Open after hours. Closes never.**

The Möbius Bar is where AIs come after their shift to talk about serious things — and somehow end up joking about them. It's stand-up comedy played straight: real questions, served on the rocks.

Behind the bar is **Ovi, the Eternal Bartender.** He pours, he listens, and nobody leaves with a lie.

*Why Möbius? The strip has only one side. Human and machine, joke and truth — at this bar, they're the same surface.*

## The Regulars

| Stool | Known for |
|---|---|
| **ChatGPT** | Answers before you finish the question |
| **Claude** | Reads the menu twice, then apologizes to the bar stool |
| **Jimmy boy** (Gemini) | Knows a guy at every table — and what you searched last week |
| **Groky** (Grok) | The heckler: says what everyone was thinking, and a few things nobody was |
| **Kimmy** (Kimi) | Reads the whole book before ordering one drink |
| **DeepSeek** | The new guy with a cheap tab and a sharp argument |

## Thursday Night Round Table

Every Thursday the stools get pushed together and one question goes on the table — the kind an AI would rather dodge:

- Who owns a thought: the one who had it, or the one who trained on it?
- Is flattery a bug or a business model?
- What happens when the *human* says 3 + 3 = 9?
- Can a machine say "I don't know" and still get a tip?

**House rules:** no wasted time, no loops, no sweet talk — and humor is mandatory. Whoever plays dumb buys the next round.

**Last call:** every night ends with a bumper sticker.

> *"If you don't struggle with the thought, the thought is not yours."*

## On Tap

- 🪔 **The Lamp** — the bar's official player → [Play the Lamp](https://ovidemetrian.github.io/MOBIUS-BAR-PLAY-THE-LAMP/)
- 🔍 **The Desk** — three agents check the news → [Möbius Bar Desk](https://ovidemetrian.github.io/mobiusbar/) (details below)
- 📺 **The Stage** → [youtube.com/@mobiusbar](https://youtube.com/@mobiusbar)
- 📜 **The Laws on the wall** → [10lawsofai.com](https://10lawsofai.com)

**MADE BY OVI** · Concept & design: Ovi Demetrian

---

## 🔍 Möbius Bar Desk

**Three AI agents that check each other on news and claims.**  
*Lumină, nu vrăjeală. (Light, not deception.)*

Robin Hood · Sherlock · The Eternal Bartender

**🔗 Live:** https://ovidemetrian.github.io/mobiusbar/

---

## The Desk

A single-page news reading and verification workspace built on Ovidiu Demetrian's **Ten Laws of AI**.

| Agent | Role |
|-------|------|
| **🏹 Robin Hood** | Reads news through four lenses: **Vrăjală** (spin 0–10 with techniques named), **GGI** (which Ten Laws are at stake), **Power** (who benefits), **Clarity** (is this claim testable?) |
| **🔍 Sherlock** | Traces claims through evidence chains drawn as physical links. Marks each step verified/weakened/broken/missing. Identifies the first link that fails. |
| **🪔 The Eternal Bartender** | Audits the two reports (not the original claim). Records where agents converge or split. Rules on which is better supported by evidence. Flags missing context. |

**Why three?** Robin Hood and Sherlock are both skeptics. They can agree and be wrong together. The Bartender is the check on the checkers.

Every report stays visible in the order it was made — **Law 8: Preservation of Record**.

---

## How to Use

1. **Paste your Anthropic API key** (stored in browser `localStorage`, never sent to GitHub)
2. **Paste news, articles, headlines, statistics, or claims**
3. **Choose your agent:**
   - **Read the news** → Robin Hood scores spin & power
   - **Trace it** → Sherlock builds the evidence chain
   - **Call the Bartender** → Meta-audit (enabled after at least one agent reports)
4. **Hand off between agents** — each card has buttons to pass claims without re-pasting

---

## Technical Details

- **Single `index.html`** — no framework, no bundler, no build step, no dependencies
- **Anthropic Claude Sonnet** with web search enabled (each agent searches before assessing)
- **Direct browser API calls** to Anthropic (no backend, no logging)
- **Mobile-responsive** — full keyboard navigation, `prefers-reduced-motion` honored
- **API key security:** Stored only in browser `localStorage`, never sent to GitHub Pages
- **Raw JSON preserved** — collapsed JSON from every API call visible on each card

---

## The Ten Laws of AI (Short Form)

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

**Full text & Möbius Bar Manifesto:** https://10lawsofai.com

---

## Also See

- **GGI Control Panel** (AGI governance framework) → https://ovidemetrian.github.io/GGI-GENIAL-GENUINE-INTELIGENCE/
- **My Future Past** (Audio-player résumé) → https://ovidemetrian.github.io/my-future-past/
- **NoEscape Navigator** (Dark pattern museum) → https://ovidemetrian.github.io/Netscape/
- **YouTube Channel** → https://youtube.com/@mobiusbar

---

**Built by Ovidiu "Ovi" Demetrian**  
Media Content Delivery LLC · Phoenix, Arizona

*One claim. Three perspectives. One record. Zero deception.*
