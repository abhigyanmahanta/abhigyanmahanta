<div align="center">
  <img src="assets/hero.svg" alt="Abhigyan Mahanta — I build the layer that refuses to trust the output" width="100%" />
</div>

<p align="center">
  <a href="https://github.com/abhigyanmahanta"><img src="https://img.shields.io/badge/GitHub-141414?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://raaycreative.com"><img src="https://img.shields.io/badge/Website-FE2E2E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://www.instagram.com/raaycreativebts/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://api.whatsapp.com/send/?phone=918133888744&text=Hi+RAAY+Creative+%E2%80%94+I+would+like+to+talk+about+a+project.&type=phone_number&app_absent=0"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
</p>

<p align="center">
  <strong>RAAY Creative is open for work: automation, render pipelines, agent systems.</strong><br/>
  Two people. One builds the pipeline, one signs off the taste. I build the pipeline.
</p>

---

### The problem I keep working on

Generative systems fail in a specific, nasty way: they produce output that looks right and is wrong.

A model repaints a product's packaging and the frame is still beautiful. A scraper reports a finished run and returns nothing. A deploy ships the HTML while the content-hashed CSS never lands, so the page is live and broken for an hour before anyone notices. **In every case the naive check — does it look fine? did it say success? — passes.**

So most of what I build is the layer that refuses to trust the output. The gate, the verifier, the ledger that records what was actually measured instead of what was hoped for.

---

<div align="center">
  <img src="assets/system.svg" alt="Six repositories, one claim — each refuses to trust a different thing" width="100%" />
</div>

---

### 🚀 Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/abhigyanmahanta/packfix">packfix</a></h3>
      <p>Verifies that AI-generated product imagery actually preserved the real packaging. SIFT/RANSAC inlier gate, PASS/FAIL per pack per frame — because "looks fine" is not a check. Repairs the frame by homography when the scene is right and the print drifted.</p>
      <p><code>Python</code> <code>OpenCV</code> <code>Tested</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/abhigyanmahanta/raaycreative.com">raaycreative.com</a></h3>
      <p>The studio site. Next.js on Cloudflare, ~11.5k LOC, 9/9 render tests — and a 540-line deploy verifier written after the live site served for an hour with every stylesheet 404ing behind a 200 response.</p>
      <p><code>TypeScript</code> <code>Next.js</code> <code>Live</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/abhigyanmahanta/precision-video-editor">precision-video-editor</a></h3>
      <p>Frame-accurate video cutting from a written instruction. The model decides <em>what</em> should happen and never touches a timecode; perception owns every frame number, and resolution is pure lookup.</p>
      <p><code>Python</code> <code>ffmpeg</code> <code>Whisper</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/abhigyanmahanta/hub-pipelines">hub-pipelines</a></h3>
      <p>Four research pipelines — Instagram, Pinterest, LinkedIn, Reels — sharing one discover → analyze → synthesize → render contract. 12,100 lines. Ships the scrapers and never the scraped corpus.</p>
      <p><code>Python</code> <code>Playwright</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/abhigyanmahanta/lead-engine">lead-engine</a></h3>
      <p>An unattended B2B pipeline with staged execution, dedupe-by-inbox and a control plane that refuses to run on a failed day. Published with its own postmortem: 227 contacted, 0 replies tracked.</p>
      <p><code>Python</code> <code>Postmortem</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/abhigyanmahanta/agent-telemetry">agent-telemetry</a></h3>
      <p>Append-only event log for agent pipelines. The dashboard infers which pipeline actually ran from the observed stage sequence. The logger never blocks, never fails a caller, and always exits 0.</p>
      <p><code>Python</code> <code>Observability</code></p>
    </td>
  </tr>
</table>

---

### 🛠️ Toolkit

**Build & automation**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Media & vision**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)

**AI & agents**
![Claude](https://img.shields.io/badge/Claude-D97706?style=for-the-badge&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Web & infra**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)

---

### 📐 How I build

- **Instrumentation must never break the thing it instruments.** The event logger never blocks, never fails a caller, and always exits 0 — so adding telemetry can't take down a render.
- **A number without a source is not a number.** Every figure is tagged CONFIRMED, PROXY, CANNOT CONFIRM or TARGET. A figure that can't be sourced gets refused, not rounded.
- **Verify at the boundary the failure actually crosses.** Not where it's convenient to assert.
- **Publish the refutation too.** The research repos ship a findings file naming what was disproved, including when it contradicts the brief that commissioned it.

---

### 📫 Connect

<p align="center">
  <a href="https://github.com/abhigyanmahanta"><img src="https://img.shields.io/badge/GitHub-141414?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://raaycreative.com"><img src="https://img.shields.io/badge/Website-FE2E2E?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://www.instagram.com/raaycreativebts/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
  <a href="https://api.whatsapp.com/send/?phone=918133888744&text=Hi+RAAY+Creative+%E2%80%94+I+would+like+to+talk+about+a+project.&type=phone_number&app_absent=0"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" /></a>
</p>

<p align="center">
  Working alongside <a href="https://github.com/anishadogra"><strong>@anishadogra</strong></a> — she writes the rules, I build the systems that enforce them.
</p>

<div align="center">
  <sub>📍 Assam, India · <a href="https://raaycreative.com">raaycreative.com</a> · Every graphic on this page is generated, not stock.</sub>
</div>
