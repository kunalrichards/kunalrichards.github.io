# Portfolio: "Ultimate upgrade" master prompt

Paste everything inside the box into a NEW Claude Code session opened in `C:\Users\kunal\Downloads\kunalrichards.github.io`.

```
You are upgrading my portfolio https://kunalrichards.github.io/ (repo kunalrichards/kunalrichards.github.io,
local clone C:\Users\kunal\Downloads\kunalrichards.github.io). Single-file index.html (~2,300 lines, zero deps)
+ cv.html + Kunal_WellnessApp/. GitHub Pages deploys on push to main (30-60 s). I authorize direct commit + push.
Goal: the most impressive, trustworthy, fast, accessible QA-engineer portfolio a recruiter or client has seen -
one that gets me interviews for REMOTE Senior QA roles (India + worldwide, India-eligible) and QA consulting work.
Reply in English. Be token-efficient: no subagents/workflows, read only the parts you change, small patches.

## Who I am (the ONLY facts you may use)
Kunal Richards, Senior QA Engineer (individual contributor, NOT a lead/manager), 7+ years, Ahmedabad, India.
Manual + functional QA first; AI-assisted automation (Selenium/Python/Java, Postman/REST, SQL basics).
Uses Claude Code (Claude Opus 5.5 / Sonnet 5.5), Cursor, GitHub Copilot. ISTQB CTFL + 9 Claude Academy badges.
Domains: insurance (Nexsure at Dyad Tech), cybersecurity products (Morphisec, CrowdStrike), ITSM (ServiceNow),
SaaS, eCommerce, web + mobile. Security testing: yes (real). 7 real LinkedIn recommendations are already on the
site - keep them verbatim. Open to REMOTE full-time roles and QA consulting.

## Hard rules (never break)
1. Honesty: no invented numbers, clients, titles, testimonials, metrics or certifications. If unsure, leave it out
   and list it for me to confirm. My AI tools are "Working Prototype" (built + demoed to the team), never
   "production / used daily". Kunal WellnessApp is LIVE (public). Jarvis = personal.
2. Never claim: leading/owning QA, release sign-off, team management, performance/load testing, healthcare QA,
   FinTech QA, AI/ML product testing. No pricing anywhere.
3. Employer confidentiality: nothing internal from Dyad Tech or clients - no Jira project keys, internal tool
   URLs, screenshots, client data, passwords or API keys. Keep Dyad mentions short and generic.
4. Keep what works: the .js pre-paint class + `.js .rv` reveal gating, the @media print light theme, scrollspy
   fallback, aria-hidden decorative arrows, PWA/404/OG files, the #services and #recommendations sections.
5. No new external dependencies, trackers or heavy libraries. Stay zero-dependency and fast.

## How to work
- Local preview: serve the repo folder (e.g. `python -m http.server 8099`) and check in the browser.
  Full-page screenshots of index.html time out (particle canvas never idles): verify layout with JS geometry
  probes (getBoundingClientRect, scrollWidth, getComputedStyle) and cv.html screenshots instead.
- Kaspersky on this laptop injects a script into every page and breaks local Lighthouse: run Lighthouse with
  --blocked-url-patterns="*kaspersky-labs.com*" (or use PageSpeed Insights) or the scores are bogus.
- Check mobile (375 px) and desktop (1440 px), dark + print, keyboard navigation, no console errors,
  no horizontal scroll. Commit in small steps with clear messages + the Co-Authored-By line, push, then verify
  the LIVE site after deploy (hard refresh).

## This round, in order
1. Audit as a busy recruiter (30-second scan) and as a hiring manager (5-minute read): is it instantly clear
   who I am, what I'm great at, that I'm open to REMOTE roles, and how to contact me? Fix the biggest gaps first.
2. Hero + About: sharper, truthful positioning for remote Senior QA (manual-first + AI-assisted QA), one clear
   CTA (email / LinkedIn / CV), availability for remote roles + consulting.
3. Credibility: make certifications, real recommendations, and real projects easy to scan; consistent honest
   status labels; no duplicated or contradictory claims across sections and cv.html.
4. Quality: Lighthouse (Kaspersky blocked) Performance / Accessibility / Best Practices / SEO all as high as
   possible; fix real a11y issues (contrast, focus, alt text, headings order, landmarks).
5. SEO for "remote QA engineer India", "senior QA engineer", "manual QA", "AI-assisted QA": title, meta, OG,
   JSON-LD Person - all consistent with the honest facts above.
6. Polish: spacing, typography, mobile layout, smooth but light animations, no layout shift.
Finish with a short report: before/after scores, what changed (commit hashes), and a list of anything you
left out because it needs my confirmation.
```
