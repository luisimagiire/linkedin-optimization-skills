# LinkedIn Profile Optimization Skills

Agent skills that turn your AI coding assistant into a LinkedIn profile consultant and career storytelling coach.

## The Problem

Most LinkedIn profiles are forgettable. They list job titles, repeat buzzwords, and fail to communicate why anyone should care. Whether you're job searching, attracting clients, or building a personal brand — your profile either works for you or against you. There's no middle ground.

Optimizing a LinkedIn profile isn't just about filling in sections. It's about knowing what to say, how to position yourself, and which details matter for your specific goal. That's what these skills do — they guide an AI agent to act as your consultant, walking you through every decision with templates, examples, and strategy.

## What's Included

### `linkedin-profile-opt`

A step-by-step consultant that walks you through optimizing your entire LinkedIn profile.

**What it does:**
- Collects your career data through a structured intake form
- Presents a personalized roadmap based on your goal (job seeking, lead generation, or thought leadership)
- Guides you through every profile section: photo, banner, URL, headline, about, experience, skills, and more
- Drafts ready-to-paste content tailored to your background and target audience
- Adapts tone, keywords, and strategy to your specific objective
- Runs a final quality review to catch gaps and inconsistencies

**Best for:** Anyone who wants to overhaul their LinkedIn profile with expert guidance, regardless of experience level.

### `linkedin-storytelling`

A career narrative builder that helps you figure out how to tell your story.

**What it does:**
- Analyzes your career data to find consistent threads, unique combinations, and differentiators
- Brainstorms 3 distinct storytelling angles with pros and cons for each
- Helps you pick the strongest angle (or combine elements from multiple)
- Refines your chosen narrative into usable formats: headline, bio, about section, elevator pitch
- Ensures your positioning is concrete, niche-specific, and evidence-backed

**Best for:** Anyone who struggles to answer "so, what do you do?" in a way that makes people lean in.

## Quick Start

### Prerequisites

An AI coding agent that supports [Agent Skills](https://agentskills.io) — Claude Code, OpenCode, Cursor, Codex, GitHub Copilot, and 40+ others.

### Install

```bash
# Install both skills
npx skills add luisimagiire/linkedin-optimization-skills --skill linkedin-profile-opt
npx skills add luisimagiire/linkedin-optimization-skills --skill linkedin-storytelling
```

### Use

Once installed, just tell your agent what you need:

**For profile optimization:**
```
I want to optimize my LinkedIn profile for [your goal]. Here's my career info: [paste or attach your details]
```

**For storytelling:**
```
Help me figure out how to tell my career story. I've been [brief career summary] and I want to position myself as [goal].
```

If you have a completed pre-fill form (from the profile optimization skill), share it with the storytelling skill for richer output.

## Recommended Workflow

1. **Start with `linkedin-storytelling`** — Figure out your positioning and narrative first
2. **Then use `linkedin-profile-opt`** — Apply that narrative across your entire profile

This ensures your headline, about section, experience bullets, and banner all tell the same consistent story.

## What You'll Need

- An existing LinkedIn profile (or willingness to create one)
- Your career history: roles, companies, dates, key achievements
- A rough idea of what you want (more jobs, more clients, more authority — or just "better")
- 2-4 hours to work through the full profile optimization

## Goal Adaptation

Both skills adapt their output based on your primary objective:

| Goal | Focus |
|---|---|
| **Job Seeking** | Keyword density for recruiter searches, skills matching, interview-ready positioning |
| **Lead Generation** | Value proposition clarity, calls to action, social proof, conversion-focused layout |
| **Thought Leadership** | Owning a niche concept, building authority, audience growth, content-driven positioning |

## How the Roadmap Was Built

The optimization roadmap isn't generic advice. It was built by scraping and transcribing the top LinkedIn expert videos on YouTube — distilling hundreds of hours of proven strategies, real case studies, and platform-specific tactics into a single structured guide. Every recommendation in the roadmap traces back to practitioners who do this professionally, not theory.

## Skill Structure

```
skills/
├── linkedin-profile-opt/
│   ├── SKILL.md                          # Consultant instructions
│   └── references/
│       ├── roadmap.md                     # Full step-by-step roadmap with templates & examples
│       └── prefill-form.md                # Client intake form
└── linkedin-storytelling/
    ├── SKILL.md                          # Storytelling process instructions
    └── references/
        └── storytelling-examples.md      # Example outputs (anonymized)
```

## License

MIT
