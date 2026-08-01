# 🏹🔍🪔 Möbius Bar Desk

**Robin Hood, Sherlock & the Bartender — three GGI agents, one claim, one record.**

*Where actual intelligence meets the artificial one.*

Built on the **Ten Laws of AI** ([10lawsofai.com](https://10lawsofai.com)) by Ovidiu Demetrian.
Principle: **LUMINĂ, NU VRĂJALĂ** — Light, not deception. Always.

**▶ Live: https://ovidemetrian.github.io/mobiusbar/**

*The capitals matter — GitHub Pages URLs are case-sensitive.*

---

## WHY TWO

An agent that only ever agrees with you is a mirror. Two agents with different
jobs can disagree — and the disagreement is where the information is.

| Agent | Job | Refuses to do |
|-------|-----|---------------|
| 🏹 **Robin Hood** | Judges. Scores vrăjală 0–10, names the technique, maps banker / miner / sucker. | Verify the evidence underneath. |
| 🔍 **Sherlock** | Verifies. Traces the claim to its sources, finds the exact link that breaks. | Say who profits. |
| 🪔 **The Bartender** | Audits *the desk*. Weighs the two against each other and names the desk's own bias. | Analyze the claim himself. |

Robin Hood and Sherlock are both skeptics — both built to find what is wrong,
which means they can agree with each other and be confidently wrong together.
The Bartender is the check on the checkers. He never sees the claim fresh: he
is handed the agents' output and asked where they part company, which one the
cited evidence actually favours, **what question neither of them asked**, and
where a desk of two skeptics tilts. His lamp burns steady when they converge
and gutters when they split.

Send a claim to either. When the card comes back it carries a **hand-off**:
Robin Hood's verdict offers *Hand to Sherlock*, Sherlock's offers *Hand to
Robin Hood*. Both results stay stacked on the desk in the order they were
made — **Law 8, preservation of record.** You are meant to read them against
each other.

---

## WHAT EACH RETURNS

**Robin Hood** — a swept vrăjală meter, the persuasion techniques actually
present, which of the Ten Laws are at stake, a banker/miner/sucker power map,
and what verifiable integrity would require.

**Sherlock** — the chain of custody drawn as physical links. Verified links
are solid, weakened are dashed, unevidenced are dotted, and the broken one is
drawn **snapped**, with everything downstream dimmed. Then **the missing
link**: the specific obtainable document, record or dataset that would settle
the question. "More research is needed" is forbidden output.

Both close with confidence as a number and the specific thing they could not
verify — Law 9, stated rather than advertised.

---

## HOW TO USE

1. Open the live link.
2. Paste your Anthropic API key (`sk-ant-...`) and press **Save**.
   Get one at [console.anthropic.com](https://console.anthropic.com).
3. Paste a claim, then press **Judge it** or **Trace it**.
4. Hand it to the other agent and compare.

**On the key:** stored in your own browser's `localStorage`, sent nowhere
except directly to Anthropic. Never logged, never sent to this site's host.
Clear the field and press Save to remove it. Each pass is one API call,
billed to you by Anthropic.

---

## TECHNICAL

Single `index.html`. No framework, no bundler, no build step. Calls the
Anthropic Messages API directly from the browser with
`anthropic-dangerous-direct-browser-access`, web search enabled, using the key
you supply. One shared design system, two agent accents. Honors
`prefers-reduced-motion` throughout; visible keyboard focus; responsive to
mobile.

Deployed on GitHub Pages. To fork: drop `index.html` in any repo, enable
Pages on `main` / root, done.

---

## LINKS

- Framework: https://10lawsofai.com
- Channel: https://youtube.com/@mobiusbar
- Smart Homes: https://smarthomesbyovi.com
- Media: https://mediacontentdelivery.com

---

*"If you did not struggle with the thought, the thought is not yours."*
*"A chain is exactly as strong as its weakest link. Say so plainly when it is weak."*
