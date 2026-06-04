# Getting Started with Claude Code

> Build websites, data tools, and automations by describing what you want in plain English. No coding experience required.

---

## What is Claude Code?

Claude Code is a command-line tool that lets you build real projects by having a conversation. You describe a problem, and it writes all the code, creates all the files, and delivers a working solution.

You say: *"Organize my messy camera photos by date and event"*  
You get: A complete system that renames files, creates folders, and builds a browsing webpage.

No programming languages. No technical jargon. No memorizing commands.

---

## Pricing

Claude Code runs on Anthropic's platform. You have two options:

| Plan | Cost | Best For |
|------|------|----------|
| Pro | $20/month | Beginners and casual builders |
| Max 5x | $100/month | Daily builders |
| Max 20x | $200/month | Heavy, all-day usage |
| API Credits | Pay-as-you-go | If you prefer not to subscribe |

**Typical project costs on pay-as-you-go:**
- Simple website: $2-10
- Data analysis: $10-25
- Complex project: $25+

Use `/cost` inside Claude Code at any time to check your spending.

---

## Installation

### Prerequisites

Nothing extra required. The installer handles everything automatically.

### Mac

Open Terminal (`Cmd + Space`, type "Terminal", press Enter), then run:

```bash
curl -fsSL https://claude.ai/install.sh | bash
```

### Windows

Open PowerShell (`Windows + R`, type "powershell", press Enter), then run:

```powershell
irm https://claude.ai/install.ps1 | iex
```

### Prefer a desktop app?

Claude Code also has a Desktop app for Mac and Windows. Download it and skip the terminal entirely. You can always switch to the terminal version later.

### Verify your installation

```bash
claude --version
```

If you see a version number, you are all set.

---

## Your First Session (5 Minutes)

**Step 1: Create a workspace**

```bash
cd Documents
mkdir my-projects
cd my-projects
```

**Step 2: Start Claude Code**

```bash
claude
```

**Step 3: Start the conversation**

Instead of a boring "hello", try this:

> *"I'm in a new project folder. Can you help me understand what we could build together and show me what you can do?"*

Claude will explain its capabilities, suggest project ideas based on your folder, and ask what problems you're trying to solve.

**When you're done:** type `/exit`

---

## Essential Terminal Commands

You only need these to get started. Don't memorize them — just refer back here.

```bash
pwd              # Where am I right now?
ls               # What's in this folder? (Mac/Linux)
dir              # What's in this folder? (Windows)
cd foldername    # Go into a folder
cd ..            # Go back up one level
mkdir newname    # Create a new folder
```

**Smart naming rules:**
- Use lowercase: `my-project` not `My Project`
- Use hyphens: `photo-organizer` not `photo organizer`
- No spaces, no special characters like `@#$%`

---

## Four Projects to Build Right Now

Pick the one that solves a real problem in your life.

### Project 1: Personal Website

```bash
mkdir portfolio-site && cd portfolio-site && claude
```

**Prompt to use:**
```
I need a simple, clean website for myself. Include sections for: my name and what I do, 
a short about me paragraph, my contact information, and 2-3 sample photos. Keep it 
professional but not boring. Make it work well on phones too. Ask me clarifying 
questions until you are 90% confident about the task before you start.
```

Expected cost: ~$10

---

### Project 2: Expense Tracker

```bash
mkdir expense-tracker && cd expense-tracker && claude
```

**Prompt to use:**
```
I have bank statements in this folder. Create something where I can see spending by 
month, day, and categories like food, transport, entertainment. Include a weekly 
summary of patterns. Anything you are not sure of midway, just ask me.
```

---

### Project 3: Purchase Decision Tool

```bash
mkdir car-purchase && cd car-purchase && claude
```

**Prompt to use:**
```
I want to buy a reliable, affordable family car within my budget of $X. My location 
is [your area]. Help me research the details, compare advantages and disadvantages, 
and create a decision framework based on my budget and preferences.
```

Works for any big purchase: car, laptop, apartment.

---

### Project 4: Data Dashboard

```bash
mkdir data-dashboard && cd data-dashboard && claude
```

**Prompt to use:**
```
I have a CSV file called [filename.csv] in this folder. Build a simple web dashboard 
that shows: the total and average of [main column], a bar chart breaking it down by 
[category column], and a filter to view by [date or category]. Use plain HTML, CSS, 
and JavaScript — no frameworks. The entire output should be a single file I can open 
directly in my browser.
```

Expected cost: $5-15 depending on dataset size.

---

## Your 30-Minute Action Plan

| Time | What to Do |
|------|-----------|
| Minutes 1-10 | Pick the project that solves your biggest current problem |
| Minutes 11-15 | Follow the setup steps exactly as written above |
| Minutes 16-25 | Have the conversation with Claude, ask for changes you want |
| Minutes 26-30 | Test your result, make one small improvement |

**Important:** Do not try to build all four projects today. Pick one, make it work, and feel proud. The goal is proving to yourself that you can build useful things without knowing how to code.

---

## Tips That Actually Matter

**Be specific.** Instead of "make a website," say "make a website for my dog walking business with services, pricing, and a contact form."

**Iterate without hesitation.** If the result doesn't feel right, say so. "This looks like it was built in 2005 — completely redesign it." Your opinion matters more than Claude's first attempt.

**Use CLAUDE.md.** Create a file called `CLAUDE.md` in your project folder with a few lines about what you're building. Claude reads it automatically every session, so it remembers your context.

**Ask freely.** "What does this section do?" and "How would I change this text?" are completely valid questions. Claude learns your preferences through conversation.

---

## Common Issues and How to Handle Them

**Unexpected costs** - Run `/cost` regularly. Set a budget before you start and stick to it.

**Claude says "done" but things are missing** - Always test what it builds. Ask "show me the actual implementation" if something seems incomplete.

**Files were changed unexpectedly** - Claude modifies files directly without asking. Keep backups of anything important. Say "undo that change" if something goes wrong.

**First attempt looks off** - That's normal. Be more specific in your follow-up. "The colors feel too corporate, switch to something warmer" is enough to get a full redesign.

---

## What You're Actually Learning

You are not learning programming. You're learning to collaborate with an AI that happens to be excellent at programming. This is a fundamentally different and much more accessible skill.

As you build, you'll naturally start seeing patterns in how Claude thinks through problems. Without trying, you'll absorb how pieces of a project fit together. The understanding follows the building — not the other way around.

---

## Resources

- [Claude Code Documentation](https://docs.claude.ai) — official docs and reference
- [Anthropic Support](https://support.claude.ai) — billing, plans, and account questions

---

*Start with the thing you've been putting off because it felt too technical.*
