# Abhigyan Mahanta

**Co-founder, [RAAY Creative](https://raaycreative.com)** — an AI-led marketing and creative studio.
A two-person studio: one builds the pipeline, one signs off the taste. I build the pipeline.

---

### The problem I keep working on

Generative systems fail in a specific, nasty way: they produce output that looks right and is wrong.

A model repaints a product's packaging and the frame is still beautiful. A scraper reports a finished run and returns nothing. A deploy ships the HTML while the content-hashed CSS never lands, so the page is live and broken for an hour before anyone notices. In every case the naive check — does it look fine? did it say success? — passes.

So most of what I build is the layer that refuses to trust the output. The gate, the verifier, the ledger that records what was actually measured instead of what was hoped for.

### Selected work

| Project | What it does |
|---|---|
| **[packfix](https://github.com/abhigyanmahanta/packfix)** | Verifies that AI-generated product imagery actually preserved the real packaging. SIFT/RANSAC inlier gate, PASS/FAIL per pack per frame — because "looks fine" is not a check. |
| **[raaycreative.com](https://github.com/abhigyanmahanta/raaycreative.com)** | The studio site. Next.js, ~11.5k LOC, 9/9 render tests, and a 540-line deploy verifier written after an outage where the HTML shipped and the assets didn't. |
| **[precision-video-editor](https://github.com/abhigyanmahanta/precision-video-editor)** | Frame-accurate video cutting from a written instruction. Five stages, JSON schemas between each, every cut resolving to an exact frame. |
| **[hub-pipelines](https://github.com/abhigyanmahanta/hub-pipelines)** | Four scrape → multimodal-analysis → report pipelines sharing one stage contract. |
| **[lead-engine](https://github.com/abhigyanmahanta/lead-engine)** | An unattended B2B lead pipeline with staged execution, cross-pipeline dedupe, and a control plane that refuses to run on a failed day. |
| **[agent-telemetry](https://github.com/abhigyanmahanta/agent-telemetry)** | Append-only event log for agent pipelines. The dashboard infers which pipeline ran from the observed stage sequence, and reports only what telemetry actually logged. |

### How I build

- **Instrumentation must never break the thing it instruments.** The event logger never blocks, never fails a caller, and always exits 0 — so adding telemetry can't take down a render.
- **A number without a source is not a number.** Every figure is tagged CONFIRMED, PROXY, CANNOT CONFIRM or TARGET. A figure that can't be sourced gets refused, not rounded.
- **Verify at the boundary the failure actually crosses.** Not where it's convenient to assert.
- **Publish the refutation too.** The research repos ship a findings file naming what was disproved, including when it contradicts the brief that commissioned it.

---

📍 Assam, India · [raaycreative.com](https://raaycreative.com)
