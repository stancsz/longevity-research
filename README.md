# Longevity Research Hub

Evidence-based health optimization protocols — personalized for your body composition, health conditions, and goals.

## Quick Start

1. **Push this repo to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   gh repo create longevity-research --public --push
   ```

2. **Enable GitHub Pages:**
   - Go to your repo on GitHub → Settings → Pages
   - Under Source, select: **Deploy from a branch**
   - Under Branch, select: **`main`** and **`/docs`** folder
   - Click Save

3. **Your site will be live at:** `https://[your-username].github.io/longevity-research/`

## What's in Here

| File/Folder | Description |
|---|---|
| `docs/index.html` | The full GitHub Pages site — all protocols, profiles, and questionnaires |
| `personalized-protocols.md` | Raw knowledge base (used by the Longevity Advisor skill) |
| `.claude/skills/longevity-advisor/` | Claude skill that generates personalized plans based on this research |

## Using the Longevity Advisor Skill

1. **Download the skill:**
   ```bash
   git clone https://github.com/stancsz/longevity-research.git /tmp/longevity-repo
   mkdir -p .claude/skills/longevity-advisor
   cp /tmp/longevity-repo/.claude/skills/longevity-advisor/SKILL.md .claude/skills/longevity-advisor/
   rm -rf /tmp/longevity-repo
   ```

2. **Load the skill** in Claude Code, Gemini, or Codex, then paste your intake form results and the agent will produce a detailed, personalized daily health and lifestyle plan.

3. **Describe yourself to get a personalized plan:**
   - Weight, height, or BMI
   - Age
   - Health conditions (diabetes, hypertension, gut issues, etc.)
   - Current medications
   - Main goals (fat loss, muscle, longevity, etc.)

## Contents

- **Body Composition Profiles** — 4 profiles (Lean, Average, Overweight, Obese) with tailored protocols
- **Health Condition Protocols** — 9 conditions: diabetes, hypertension, cholesterol, inflammation, sarcopenia, bone health, gut dysbiosis, mental health, sleep
- **Age-Based Modifications** — Optimizations for ages 25-40, 40-55, 55-70, 70+
- **Biomarker Targets** — Key numbers to track for longevity
- **Daily Timing Protocol** — Hour-by-hour template
- **Extended Intake Questionnaire** — For deep personalization

## Disclaimer

These are general guidelines based on published research — always consult a healthcare provider for personal medical advice, especially if you have existing conditions or take medications.

---

*Last updated: April 2026*