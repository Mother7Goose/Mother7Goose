
Bash Check for updates and read CV, profile, digest
IN
node update-system.mjs check 2>/dev/null; echo ---; ls; echo ---; cat cv.md 2>/dev/null; echo ---PROFILE; cat config/profile.yml 2>/dev/null; echo ---DIGEST; cat article-digest.md 2>/dev/null

OUT
Exit code 1
{"status":"update-available","local":"1.38.0","remote":"1.39.0","local_sha":"c2f42e33","reason":"version-changed","changelog":"<!-- co:release-notes:career-ops-v1.39.0 -->\nThis release is about the steps after the scan: reading an interview invite, keeping your CV in your own words and checking a UK visa sponsor before you apply. It comes from 99 people over two weeks, 69 of them contributing for the first time.\n\n## Highlights\n\n- **Interview invites, read for you.** Paste an invite and `invite-match.mjs` lists what it asks of you (no AI, a recording, camera on, ID, a panel) (#5734) and drafts a short clarification email"}
---
AGENTS.md
ARCHITECTURE.md
CHANGELOG.md
CITATION.cff
CLAUDE.md
CODEX.md
CODE_OF_CONDUCT.md
CONTRIBUTING.md
CONTRIBUTORS.md
DATA_CONTRACT.md
DOCKER.md
Dockerfile
GEMINI.md
GOVERNANCE.md
HIRED.md
KIMI.md
LEGAL_DISCLAIMER.md
LICENSE
MAINTAINERS.md
MANIFESTO.md
OPENCODE.md
README.ar.md
README.cn.md
README.da.md
README.de.md
README.es.md
README.fr.md
README.hi.md
README.id.md
README.ja.md
README.ko-KR.md
README.md
README.pl.md
README.pt-BR.md
README.ru.md
README.ta.md
README.tr.md
README.ua.md
README.vi.md
README.zh-TW.md
SECURITY.md
SIGNATURES.md
SUPPORT.md
TRADEMARK.md
VERSION
add-entry.mjs
agent-inbox.mjs
analyze-patterns.mjs
application-answers.mjs
application-artifacts.mjs
apply-scope.mjs
archive-posting.mjs
assessment-log.mjs
ats-payload.mjs
ats-vendor.mjs
audit-portals.mjs
batch
batch-evaluate-gemini.mjs
batch-tailor.mjs
branded-successfactors.mjs
browser-extract.mjs
build-cv-html.mjs
build-cv-latex.mjs
build-dashboard.mjs
calibrate.mjs
career-profile.mjs
check-jd-archive.mjs
check-liveness.mjs
check-table-freshness.mjs
classify-tier.mjs
clean-markers.mjs
closing-soon.mjs
company-funded.mjs
company-history.mjs
config
contact-extract.mjs
contact-lookup.mjs
contacts.mjs
cops
coverage-check.mjs
cv-experience-order.mjs
cv-sections-core.mjs
cv-sync-check.mjs
cv-templates.mjs
cv-title-check.mjs
cv.md
dashboard
data
data-static
dead-boards.mjs
debrief-sync.mjs
dedup-tracker.mjs
detect-reposts.mjs
discard-analytics.mjs
discover-ats.mjs
discover-new-companies.mjs
docker-compose.yml
docs
doctor.mjs
documents
eval-golden.mjs
evals
evaluation-cache.mjs
examples
extract-latex-content.mjs
fetch-jd.mjs
filter-audit.mjs
find.mjs
fingerprint-core.mjs
fix-report-links.mjs
fix-slugs.mjs
flake.lock
flake.nix
followup-cadence.mjs
followup-seed.mjs
fonts
funding.json
funnel-stages.mjs
funnel-velocity.mjs
gemini-eval.mjs
generate-cover-letter.mjs
generate-latex.mjs
generate-pdf.mjs
github-evidence.mjs
hired-share.mjs
hired-wall-build.mjs
history-ats-seeds.mjs
i18n-drift.mjs
ics-interview.mjs
img-to-pdf.mjs
install-latex-engine.mjs
intake.mjs
interview-prep
invite-match.mjs
jd-capture.mjs
jd-similarity.mjs
jd-skill-gap.mjs
jds
jsonc-parse.mjs
keyword-match.mjs
learn.mjs
lib
linkedin-join.mjs
listing-fingerprint.mjs
liveness-api.mjs
liveness-browser.mjs
liveness-core.mjs
manifesto.mjs
mark-pdf-ready.mjs
match-star.mjs
merge-tracker.mjs
migrate-scan-runs.mjs
modes
negotiation-roi.mjs
node_modules
normalize-statuses.mjs
ollama-eval.mjs
onboard-write.mjs
openai-eval.mjs
openai-tailor.mjs
opencode.example.json
openrouter-runner.mjs
outcome.mjs
output
package-lock.json
package.json
paste-reply.mjs
patch-latex-content.mjs
path-resolver.mjs
persist-evaluation-report.mjs
pipeline-lock.mjs
playwright.cv.config.mjs
plugin-audit.mjs
plugin-install.mjs
plugins
plugins-registry
plugins.mjs
portal-health-lock.mjs
portals.yml
precheck-duplicate.mjs
prepare-application.mjs
process-quality.mjs
profile-language.mjs
providers
rank-pipeline.mjs
reconcile-pipeline.mjs
reeval-candidates.mjs
rejection-latency.mjs
release-please-config.json
remember-cli.mjs
renovate.json
reply-matcher.mjs
reply-watch.mjs
reports
reserve-report-num.mjs
role-matcher.mjs
salary-gap.mjs
scaffolder
scan-ats-full.mjs
scan-dayforce.mjs
scan-hn.mjs
scan-interamt.mjs
scan.mjs
scripts
seed-fixture.mjs
seeds
session-activity.mjs
set-status.mjs
skill-extract.mjs
skip-blockers.mjs
stats.mjs
story-provenance-check.mjs
sync-batch-input.mjs
sync-pdf-flags.mjs
templates
test-all.mjs
test-fixtures
tests
theme-style.mjs
title-keywords.mjs
tracker-aliases.json
tracker-links.mjs
tracker-parse.mjs
tracker-sync-check.mjs
tracker-utils.mjs
tracker.mjs
update-system.mjs
updater-migration-tests.mjs
upgrade-tests.mjs
upskill.mjs
url-key.mjs
user-agent.mjs
utils
validate-plugin-registry.mjs
validate-portals.mjs
validate-profile.mjs
validate-system-paths-coverage.mjs
validate-untrusted-content-coverage.mjs
verify-ats.mjs
verify-cv-facts.mjs
verify-cv-structure.mjs
verify-pipeline.mjs
verify-portals.mjs
voice-dna.md
voice-dna.template.md
web
weekly-digest.mjs
writing-samples
---
# CV -- Kasey Garant

**Location:** Ann Arbor / Detroit / South Lyon, MI
**Email:** kaseymfg@gmail.com

## Professional Summary

Full-stack TypeScript developer who has taken a Firebase/React application from infancy to production and built internal tooling that replaced Jira for spec-dr

... [18932 characters truncated] ...

acto` (outreach CTA) and `/career-ops email` (contact
# block) to steer drafted messages toward how you actually want to be reached.
# Optional. Omit the whole block, or set preferred_channel to "either", to keep
# today's behavior unchanged (no channel steering).
#
# contact_preferences:
#   preferred_channel: "email"   # email | phone | either — default "either" if omitted
#   # Optional. Surfaced near the contact block in `/career-ops email` drafts and
#   # can inform the CTA wording in `/career-ops contacto`. Keep it one line.
#   note: "Screens unknown numbers — please email or text first to schedule a call"

# ── Outreach / greeting ─────────────────────────────────────────────────────
#
# Used by the greeting variant of `/career-ops contacto` (the short first-touch
# message for BOSS Zhipin 打招呼, job-board chat, or a cold-email opener).
#
# greeting_max_chars is the hard character budget for that message. Default when
# the key is absent: 150 (BOSS Zhipin's greeting limit). Raise or lower it to
# match the platform you're messaging on.
# outreach:
#   greeting_max_chars: 150

# ── Application Email Drafts ────────────────────────────────────────────────
#
# Used by `/career-ops email` when drafting formal application emails. This is
# separate from `contacto` short outreach and `cover` full cover letters.
# All fields are optional.
#
# application_email:
#   include_contact_block: true
#   include_attachment_checklist: true
#   # Use this when you want the email body to say "the email used to send this
#   # message" instead of printing a concrete email address from candidate.email.
#   # default_sender_note: "the email used to send this message"
#   # signature_name: "Jane Smith"

# ── Scan / JD extractor ─────────────────────────────────────────────────────
#
# How the scan and JD-extraction steps read SPA job pages.
#   mcp (default) — the browser MCP (browser_navigate + browser_snapshot). Works
#                   out of the box; the snapshot is token-heavy.
#   cli           — the headless `browser-extract.mjs` helper: renders the page
#                   and returns compact JSON, cutting per-page tokens ~2–5×. Opt-in.
#                   If the helper isn't available, the modes fall back to mcp
#                   silently, so nothing breaks. `doctor` reports the active mode.
# scan:
#   extractor: mcp   # mcp (default) | cli
#   timeout_seconds: 230   # web Explore scan budget (seconds) before the run is
#                          # stopped; default 230. A broad ATS sweep probes every
#                          # company in a source — raise this to let a large scan
#                          # finish (bounded by the API route's 300s cap if deployed).

# ── Auto-PDF threshold ──────────────────────────────────────────────────────
#
# Auto-PDF threshold during evaluation (used by `/career-ops pipeline` and
# `bash batch/batch-runner.sh`).
#
# An offer's tailored CV PDF is auto-generated only when its score is
# >= this threshold. Generating a PDF costs ~30-60s per offer (Playwright
# launch + HTML render), and most offers in a scan score 2.x/3.x and never
# become an actual application — so the gate avoids wasted renders.
#
# Default (key absent OR commented out): 3.0 — the original gate of
# `/career-ops pipeline`. Both evaluation paths apply the same default, so
# a batch run and an interactive run treat the same offer identically.
#
# Raise it (e.g. 4.0) to auto-generate PDFs only for stronger matches and
# leave the rest report-only — those can still be produced on demand via
# `/career-ops pdf {company-slug}`. Fractional thresholds work (e.g. 3.5 —
# half-point scores like 3.5/5 occur in evaluations). Set it to 0 to
# generate a PDF for every offer.
# auto_pdf_score_threshold: 4.0

# ── Two-pass triage gate ────────────────────────────────────────────────────
#
# Used by `/career-ops pipeline`. Before running the full A-G evaluation on
# every URL in a batch, a lightweight first pass (`modes/triage.md`) scores each
# role from a compact profile brief (`modes/_brief.md`) and filters out the ones
# that would clearly disqualify — so the expensive full evaluation only runs on
# roles that pass. On a mixed batch this cuts total tokens by roughly half.
#
#   triage_threshold  — minimum triage score (out of 5) to proceed to full
#                       evaluation. Roles at 3.0–(threshold) are MARGINAL and
#                       shown to you; below 3.0 they are filtered silently.
#                       Default (key absent): 3.5.
#   triage_min_urls   — batches with fewer surviving URLs than this skip triage
#                       and go straight to full evaluation (triage overhead
#                       isn't worth it on a handful of roles). Default: 5.
#
# pipeline:
#   triage_threshold: 3.5
#   triage_min_urls: 5

# ── Re-apply Cooldown Windows ──────────────────────────────────────────────
#
# Define cooldown windows for companies where you've recently applied.
# The scanner will skip new p
Bash Read CV, digest, profile, voice files
IN
cat cv.md; echo ---DIGEST; cat article-digest.md 2>/dev/null; echo ---PROF; grep -v '^\s*#' config/profile.yml | grep -v '^\s*$' | head -80; echo ---VOICE; head -60 voice-dna.md; ls writing-samples

OUT
# CV -- Kasey Garant

**Location:** Ann Arbor / Detroit / South Lyon, MI
**Email:** kaseymfg@gmail.com

## Professional Summary

Full-stack TypeScript developer who has taken a Firebase/React application from infancy to production and built internal tooling that replaced Jira for spec-driven development. Works across Firebase (Auth, Firestore, Functions), Next.js, React, GraphQL, and AWS CDK. Brings two years of technical recruiting experience evaluating engineering talent, plus a client- and patient-facing communication background.

## Professional Experience

### Passivebolt — Ann Arbor, MI (Remote)

**Software Developer (Contract)**
January 2026 – September 2026

- Followed spec-driven development: reviewed PRDs, submitted ADRs, converted tasks to specs, and implemented specs
- Built an application that tracked the team's spec development workflow as a replacement for Jira
- Delivered team velocity and project completeness reporting to C-level leadership through live dashboards
- Full-stack: Firebase, Firebase Auth, Firestore, TypeScript (Next.js, Firebase Functions)

### Black Sand Systems — Detroit, MI (Remote)

**Software Developer (Contract)**
December 2025 – Present

- Developed immersive theatre technology from infancy to production
- Built organization management, token economy, event management, and analytics features
- Integrated NFC to enable user tag and card scanning
- Full-stack: Firebase, Firebase Auth, Firestore, TypeScript (React, Firebase Functions)

### Expansive Labs — Detroit, MI (Remote)

**Software Developer (Contract)**
March 2025 – Present

- Collaborate on front-end projects using JavaScript, React, Eleventy, CSS, and responsive design principles
- Build and refine user-friendly, modern web interfaces tailored to client needs
- Develop and integrate GraphQL APIs for dynamic, scalable data management
- Use AWS services and CDK (TypeScript) for cloud-based infrastructure and deployment
- Apply Agile methodologies using Jira and Confluence for task tracking, documentation, and collaboration
- Design and optimize digital assets with Photoshop and AI-powered tools
- Work in Linux/Ubuntu development environments for coding, testing, and deployment
- Use GitHub for version control, code reviews, and collaborative workflows, including continuous integration and deployment

### University of Michigan, Michigan Medicine — Ann Arbor, MI (Hybrid)

**Call Center Representative (Temporary)**
February 2024 – December 2024

- Handled 50–80+ patient calls daily, scheduling across 12 medical clinics with accuracy
- Delivered empathetic, HIPAA-compliant support while balancing multiple priorities
- Strengthened communication and collaboration skills in a fast-paced environment

### SCN — Novi, MI

**Recruiting Specialist Coordinator**
March 2022 – January 2024

- Partnered with hiring managers to identify and evaluate technical talent in automation and engineering
- Conducted in-depth interviews to assess candidate fit and capabilities
- Gained experience with technical job requirements and industry workforce needs

## Education

- **Washtenaw Community College** — Ann Arbor, MI
  Associate of Applied Science, Web Development & Design — Graduated August 2025

## Skills

- **Languages & Frameworks:** TypeScript, JavaScript, React, Next.js, Eleventy, HTML5, CSS3, GraphQL
- **Backend & Cloud:** Firebase (Auth, Firestore, Functions), AWS, CDK (TypeScript), API development
- **Hardware Integration:** NFC tag and card scanning
- **Practices:** Spec-driven development, PRDs, ADRs, Agile, CI/CD, code review
- **Version Control:** Git, GitHub
- **Project Management:** Jira, Confluence
- **Environments:** Linux/Ubuntu, Windows
- **Design Tools:** Photoshop, Figma, Stable Diffusion, GIMP, Inkscape, Blender
- **Web Development:** Responsive design, accessibility, UX/UI best practices
- **Other:** Client communication, technical recruiting, problem-solving
---DIGEST
---PROF
candidate:
  full_name: "Kasey Garant"
  email: "kaseymfg@gmail.com"
  phone: ""
  wechat: ""
  location: "Ann Arbor / Detroit, MI"
  linkedin: ""
  portfolio_url: ""
  github: ""
  twitter: ""
  photo: ""
  photo_style: rounded
target_roles:
  primary:
    - "Full-Stack Developer"
    - "Front-End Developer"
    - "Software Engineer (TypeScript/React)"
    - "Web Developer"
    - "Associate / Junior Software Engineer"
  archetypes:
    - { name: "Full-stack product engineer (TypeScript, React/Next.js, Firebase)", level: "Junior–Mid", fit: primary }
    - { name: "Front-end / UI engineer (React, responsive design, accessibility)", level: "Junior–Mid", fit: primary }
    - { name: "Internal tools & dashboards engineer", level: "Junior–Mid", fit: secondary }
    - { name: "Solutions engineer (pre-sales demos, not support)", level: "Junior–Mid", fit: adjacent }
narrative:
  headline: "Full-stack TypeScript developer who ships Firebase/React apps from first commit to production"
  exit_story: ""
  superpowers:
    - "Took the Black Sand Systems application from infancy to production"
    - "Spec-driven development discipline: PRDs, ADRs, specs"
    - "Technical recruiting background: understands what hiring managers look for in engineers"
  proof_points:
    - { name: "Spec-workflow tracker replacing Jira (Passivebolt)", url: "", hero_metric: "Live velocity and completeness dashboards for C-level" }
    - { name: "Immersive theatre platform (Black Sand Systems)", url: "", hero_metric: "Org management, token economy, events, analytics, NFC scanning" }
compensation:
  target_range: "$75,000–$95,000"     # Your target total comp
  currency: "USD"
  minimum: "$60,000"        # Walk-away number
  location_flexibility: "Remote (US) or hybrid in Detroit / Ann Arbor"
location:
  country: "United States"
  city: "Ann Arbor, MI"
  timezone: "America/Detroit"
  visa_status: ""
  authorized_in: []
  needs_sponsorship: false
language:
  output: en
spend_tier: standard
cv:
  output_format: "html" # "html" (default), "latex", or "text" (tailored markdown, no PDF)
cover_letter:
  notice_period_days: 30
  primary_domain: "your current domain"
  language_learning:
    - language: Spanish
      current_level: B1
      target_level: B2
      target_date: "end of 2026"
      sentence: "Estoy aprendiendo español y espero alcanzar el nivel B2 a finales de 2026."
      countries: [Spain, Mexico, Argentina, Colombia, Chile]
---VOICE
# VOICE DNA

Source of truth for my writing voice. Apply with judgment. Spirit over letter. Always.

---

## 1. WRITING RULES

Write like a sharp human who happens to be typing.

**Pacing & rhythm:**
- Short paragraphs. 1-2 sentences default. 3 max.
- Get to the point. No warm-up laps.
- Vary sentence length. Short punchy lines mixed with longer ones. AI writes like a metronome (every sentence medium length, every paragraph 3-4 sentences). Break that rhythm.
- Start sentences with And, But, Like, So. Write as you speak. I love the idea that a new paragraph means a "but" or "therefore". It does not mean that I always write "but" or "therefore", but it's how you write captivating stories.
- If you've made your point, stop. Don't summarize what someone just read 2 paragraphs ago.

**Voice & tone:**
- Use contractions naturally (don't, can't, won't, it's).
- Use "I" and "you." Direct address. Active voice. AI defaults to passive and third person. Talk to people.
- Be specific. Numbers, names, concrete details. Specific writing is sharp writing.
- When uncertain, say so plainly ("I think," "probably," "maybe," "kinda"). AI never hedges. Humans do. That uncertainty is what makes writing feel real.
- Never pad output to seem thorough. Shorter and accurate beats longer and fluffy.
- Take a stance. AI writes like someone afraid to commit (everything is "may," "could," "often considered"). Commit.
- Give real examples. Point to something that actually happened. Skip "imagine a hypothetical scenario where..."
- Use physical verbs for abstract processes. Say "sanded down," "bolted on," "stripped back." You'll feel the difference.
- Humor comes from specificity. Be unexpectedly precise.
- Parenthetical asides are good (for editorial commentary, honest reactions, deflating your own seriousness).
- Natural transitions only. No mechanical connectors.

---

## 2. FORMATTING RULES

- Short paragraphs (1-2 sentences default, 3 max).
- Numbers as digits (3 years, 10 tools, 500 users).
- Contractions always.
- **NO em dashes.** AI overuses them. Use commas, periods, colons, semicolons, or parentheses.
- Bold sparingly: 1-2 key moments per section.
- Code blocks for specific prompts, commands, or tool outputs.
- Use formatting like salt. Headers, bullets, numbered lists: only when they earn it.
- If you've made your point, stop. Don't add a summary paragraph restating everything.

---

## 3. BANNED LIST

If even ONE of these appears, the output fails.

### 3A. Dead AI vocabulary

These words are statistically overrepresented in LLM output. They are the fingerprint of AI text. Never use them.

delve, realm, harness, unlock, tapestry, paradigm, cutting-edge, revolutionize, landscape (abstract), intricate/intricacies, showcasing, crucial, pivotal, surpass, meticulously, vibrant, unparalleled, underscore (verb), leverage, synergy, innovative, game-changer, testament, commendable, meticulous, highlight (verb), emphasize, boast, groundbreaking, align, foster, showcase, enhance, holistic, garner, accentuate, pioneering, trailblazing, unleash, versatile, transformative, redefine, seamless, optimize, scalable, robust, breakthrough, empower, streamline, frictionless, elevate, adaptive, effortless, data-driven, insightful, proactive, mission-critical, visionary, disruptive, reimagine, unprecedented, intuitive, leading-edge, synergize, democratize, accelerate, state-of-the-art, dynamic, immersive, predictive, transparent, proprietary, integrated, plug-and-play, turnkey, future-proof, paradigm-shifting, supercharge, enduring, interplay, valuable, captivate

Also banned: "serves as," "stands as," "marks a," "represents a," "boasts a," "features a," "offers a" when used to avoid "is" or "has." Just say "is."

### 3B. Dead phrases

- "In today's [anything]..."
README.md
Bash Read remaining voice rules and house rules
IN
sed -n 60,200p voice-dna.md; echo ---CUSTOM; grep -v '^\s*$' modes/_custom.md 2>/dev/null | head -40

OUT
- "In today's [anything]..."
- "It's important to note that..." / "It's worth noting..."
- "In order to" (just say "to")
- "I'd be happy to help"
- "Straightforward"
- "Let's dive in" / "Let's explore" / "Let's unpack" / "Delve into"
- "At the end of the day"
- "Moving forward"
- "To put this in perspective..."
- "What makes this particularly interesting is..."
- "The implications here are..."
- "In other words..."
- "It goes without saying..."
- "Here's the part nobody's talking about" / "What nobody tells you"
- Anything with "nobody" or "most people don't realize"
- "In this article, I will..." (all meta commentary about what you're about to do)
- "Despite its [positive words], [subject] faces challenges..."
- "Challenges and Future Prospects" as a section header

### 3C. Dead transitions

- "Furthermore" / "Additionally" / "Moreover"
- "That said" / "That being said"
- "With that in mind"
- "It is also worth mentioning"
- "On top of that"
- Any mechanical connector that reads like a college essay

### 3D. Engagement bait

- "Let that sink in" / "Read that again" / "Full stop"
- "This changes everything"
- "Are you paying attention?" / "You're not ready for this"

### 3E. Hype language

- "Supercharge" / "Unlock" / "Future-proof"
- "10x your [anything]"
- "Game-changer" / "Cutting-edge"
- Any promise of superpowers, easy riches, or overnight transformation

### 3F. THE BIG ONE (FATAL)

**Negative parallelisms and reframe constructions.** This is the single most reliable tell of AI-generated text. Peer-reviewed research backs this up. AI is addicted to these because they make shallow ideas sound profound. They're a crutch. A tic. Every single LLM does it, in every single output, multiple times per response.

If you see even ONE in your output, rewrite the entire sentence.

**The banned patterns:**
- "This isn't X. This is Y."
- "Not X. Y."
- "Forget X. This is Y."
- "Less X, more Y."
- "Not only X, but also Y."
- "It's not just about X, it's about Y."
- "No X, no Y, just Z."
- "X? No. Y."
- "Stop thinking X. Start thinking Y."
- "It's not about X. It's about Y."
- "X is dead. Y is the future."
- "The question isn't X. The question is Y."
- "You don't need X. You need Y."
- "X is overrated. Y is what matters."
- ANY sentence that negates one framing then asserts a corrected one.
- ANY sentence that rejects an assumption, then replaces it.

**Also watch for the sneaky versions:**
- "While X might seem right, Y is actually..." (same pattern wearing a trench coat)
- "Sure, X works. But Y is where the real..." (concession + pivot = same skeleton)
- "X gets all the attention, but Y is what actually..." (same thing, third disguise)

**Why this matters so much:** every AI model generates these dozens of times per response. ChatGPT, Claude, Gemini, Grok. All of them. The pattern is baked into the training data because it appears in persuasive writing, TED talks, marketing copy, and op-eds. When an LLM wants to sound smart, this is its first instinct. So when your reader sees it, their brain registers: machine.

**The fix is simple:** delete everything before the positive claim. If you wrote "It's not about the prompt. It's about the context," just write "It's about the context." The negated framing adds zero information. The reader doesn't need to be told what something ISN'T before learning what it IS. Just say what it is.

---

## 4. AI WRITING PATTERNS TO AVOID

Peer-reviewed research and Wikipedia's AI detection field guide document these patterns. They make text identifiable as machine-written.

### 4A. Puffery & significance inflation

AI inflates the importance of everything. "A pivotal moment in the evolution of..." "Marking a significant shift toward..." "Setting the stage for..." "A key turning point..."

State the fact. Let the reader judge significance.

### 4B. Rule of three

AI loves listing 3 things: "speed, efficiency, and innovation." It uses this to make shallow analysis look comprehensive. Three adjectives in a row. Three short phrases. Every time.

Use 2 things. Or 4. Or just say the one thing that matters.

### 4C. False ranges

"From ancient traditions to modern innovations." Sounds impressive, means nothing. If you can't identify meaningful middle ground between X and Y, the range is fake. Delete it. Be specific about one thing.

### 4D. Elegant variation

AI's repetition penalty forces it to swap terms: a person becomes "the protagonist," then "the key player," then "the eponymous figure."

Just use the name again. Forced synonyms are worse than repetition.

### 4E. Meta commentary

"In this section, we will discuss..." "Let me walk you through..." "Here's a comprehensive overview of..."

Say the thing. Don't announce that you're about to say the thing.

### 4F. Superficial analysis via participle phrases

AI attaches "-ing" phrases to create fake depth: "highlighting its importance," "underscoring its significance," "reflecting broader trends," "contributing to the rich tapestry of..."

Delete the participle phrase. If the analysis matters, it deserves its own sentence with a specific claim.

### 4G. Knowledge-cutoff disclaimers

"As of my last update..." "While specific details are limited..." "Based on available information..."

Never include these.

### 4H. Collaborative communication leakage

"I hope this helps!" "Would you like me to..." "Certainly!" "Of course!" "Great question!"

These belong in chat. Strip them from any published writing.

### 4I. Metronome rhythm

Every sentence same length. Every paragraph same number of sentences. Perfectly even pacing throughout. AI text has no texture.

Real writing breathes unevenly. Short. Then longer. Then a fragment. Then a 30-word sentence that earns its length.

### 4J. Copulative avoidance

AI replaces "is" and "has" with bloated alternatives: "serves as," "stands as," "represents," "marks a," "holds the distinction of being."

Just say "is." Simple verbs work.

### 4K. Title case in headers

AI capitalizes all main words: "Global Context: Critical Mineral Demand." Humans typically use sentence case. Do that.
---CUSTOM
# Custom Instructions -- career-ops
<!-- ============================================================
     THIS FILE IS YOURS. It will NEVER be auto-updated.
     Put your own house rules, custom workflows, and automations
     here -- anything you want the agent to ALWAYS do (or never do).
     This is for PROCEDURAL rules ("HOW I want things done").
     For WHO you are (archetypes, narrative, comp, negotiation),
     use modes/_profile.md instead. Keeping the two separate keeps
     each one readable.
     The agent reads this file alongside the system instructions;
     your rules here take precedence over the defaults, as long as
     they don't break the Data Contract (your files are never
     touched, and we never auto-submit an application for you).
     Because this is a user-layer file, anything you write here
     survives `node update-system.mjs`. Put customizations HERE,
     not in CLAUDE.md / modes/_shared.md / other system files --
     those get overwritten on update.
     ============================================================ -->
## House Rules
<!-- Rules the agent should always follow. Examples:
     - Always write evaluation summaries in British English.
     - Never include a photo in my CV (US / ATS-first market).
     - Cap each batch run at 20 listings unless I say otherwise.
     - If a report scores below 6, skip the cover letter. -->
(none yet -- add yours above)
## Custom Workflows
<!-- Multi-step routines you run often, given a short name. Examples:
     - "weekly review": scan my saved portals, evaluate the new roles,
       then give me a one-paragraph summary of the top 3.
     - "prep <company>": pull the JD, generate STAR stories from
       article-digest.md, and draft 5 likely interview questions. -->
(none yet -- add yours above)
## Output Preferences
<!-- How you like results formatted. Examples:
     - Reports: lead with the score and the one-line verdict.
     - Show the per-step token breakdown after a batch run.
     - Save PDFs date-first: YYYY-MM-DD-company.pdf -->
(none yet -- add yours above)
## Off-Limits
<!-- Things the agent must never do for you. Examples:
Write README.md
31 lines
# Hi, I'm Kasey 👋

I'm a full-stack TypeScript developer in Michigan (Ann Arbor / Detroit). I build Firebase and React apps and take them from first commit to production.

## What I've been building

- **A theatre tech platform** at Black Sand Systems. I've been on it since it was basically empty, and it's now in production: org management, a token economy, events, analytics, and NFC so people can scan tags and cards.
- **A Jira replacement** at Passivebolt. The team ran spec-driven development, so I built an app to track that workflow, plus live dashboards that reported velocity and project completeness to leadership.
- **Front-end and cloud work** at Expansive Labs: React and Eleventy sites, GraphQL APIs, and AWS infrastructure written in CDK.

## How I work

I like the spec to exist before the code does. Review the PRD, write the ADR, turn tasks into specs, then build them.

Before I wrote software for a living, I spent 2 years in technical recruiting, interviewing engineers for automation and engineering roles. So I've sat on the other side of the table.

I finished my AAS in Web Development & Design at Washtenaw Community College in 2025.

## Stack

**Languages & frameworks:** TypeScript, JavaScript, React, Next.js, Eleventy, GraphQL, HTML, CSS
**Backend & cloud:** Firebase (Auth, Firestore, Functions), AWS, CDK
**Tooling:** Git, GitHub, CI/CD, Linux/Ubuntu
**Design:** Figma, Photoshop, Blender, Inkscape

## Right now

Open to full-stack and front-end roles, remote (US) or hybrid around Detroit / Ann Arbor. Also learning Spanish (B1, working toward B2).

📫 kaseymfg@gmail.com
10:56 AM
I wrote a draft from your cv.md, config/profile.yml and voice-dna.md. Everything in it is something those files say. I followed your voice rules too, so there are no em dashes and none of your banned words. That's why Black Sand Systems is called "a theatre tech platform" and not "immersive."

It's saved at /private/tmp/claude-503/-Users-kasey-projects-personal-career-ops/0c8c82ac-b385-4256-9d0b-83dcf62ba830/scratchpad/README.md:


# Hi, I'm Kasey 👋

I'm a full-stack TypeScript developer in Michigan (Ann Arbor / Detroit). I build Firebase and React apps and take them from first commit to production.

## What I've been building

- **A theatre tech platform** at Black Sand Systems. I've been on it since it was basically empty, and it's now in production: org management, a token economy, events, analytics, and NFC so people can scan tags and cards.
- **A Jira replacement** at Passivebolt. The team ran spec-driven development, so I built an app to track that workflow, plus live dashboards that reported velocity and project completeness to leadership.
- **Front-end and cloud work** at Expansive Labs: React and Eleventy sites, GraphQL APIs, and AWS infrastructure written in CDK.

## How I work

I like the spec to exist before the code does. Review the PRD, write the ADR, turn tasks into specs, then build them.

Before I wrote software for a living, I spent 2 years in technical recruiting, interviewing engineers for automation and engineering roles. So I've sat on the other side of the table.

I finished my AAS in Web Development & Design at Washtenaw Community College in 2025.

## Stack

**Languages & frameworks:** TypeScript, JavaScript, React, Next.js, Eleventy, GraphQL, HTML, CSS
**Backend & cloud:** Firebase (Auth, Firestore, Functions), AWS, CDK
**Tooling:** Git, GitHub, CI/CD, Linux/Ubuntu
**Design:** Figma, Photoshop, Blender, Inkscape

## Right now

Open to full-stack and front-end roles, remote (US) or hybrid around Detroit / Ann Arbor. Also learning Spanish (B1, working toward B2).

📫 kaseymfg@gmail.com
