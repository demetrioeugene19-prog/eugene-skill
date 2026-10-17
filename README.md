# EUGENE: a Claude Code skill for beginners

**Think first. Test first. Ask first.**

EUGENE turns the way you already talk about a task into a complete, professional brief for Claude
Code. Claude then thinks like an expert, tests small, and asks you before anything goes live. You
do not need to know how to write prompts. You just say what you need.

Made by Eugene Demetrio for friends and churchmates learning Claude Code.

---

## The three layers of AI

```
  3  AGENTIC AI        It does the work.        Claude Code, with skills and MCPs   <- EUGENE works here
  2  AI AUTOMATION     It runs 24/7 on rules.   Workflows, reminders, follow-up texts
  1  AI CHAT           It answers.              ChatGPT, Claude chat
```

Most people stay at layer 1: they ask, the AI answers, and they do the work by hand. Claude Code
works at layer 3. EUGENE helps you give it the right task, so the repetitive work gets done for you.

---

## What you need

- **Claude Code** installed, with a paid Claude plan (Pro or higher).
- About 2 minutes to install EUGENE.

## Install

**Option 1: one command (Mac or Windows)**

Open Terminal (Mac) or PowerShell (Windows) and run:

```
npx skills add demetrioeugene19-prog/eugene-skill -g -s eugene -a claude-code -y
```

It installs EUGENE for all your projects, with no questions.

Or simply paste this into the Claude chat in VS Code:

```
Please install the EUGENE skill by running this command: npx skills add demetrioeugene19-prog/eugene-skill -g -s eugene -a claude-code -y
Then tell me in simple words how to start a new chat and test it with /eugene.
```

**Option 2: copy the folder**

1. Download this repository (green **Code** button, then **Download ZIP**) and unzip it.
2. Copy the folder `skills/eugene` into your Claude skills folder:
   - Mac: `~/.claude/skills/`
   - Windows: `C:\Users\YOUR-NAME\.claude\skills\`
3. Restart Claude Code.

Check it worked: in Claude Code, type `/eugene`. It should greet you.

---

## How to use it

Type `/eugene`, then your task in your own words. English, Tagalog or Bisaya are all fine.

```
/eugene new leads from the website form are not getting the welcome text
/eugene help me reply to a client who has not answered my proposal for 5 days
/eugene explain what MCP is
/eugene improve this prompt: make me a landing page
```

What happens next:

1. **EUGENE writes your brief:** task, who uses it, how it works today, what "done" looks like,
   what you have, your limits. It asks at most three short questions if something is missing.
2. **It thinks first:** what to fix, the goal, the plan, how it will prove it worked, and what could
   go wrong.
3. **You say yes,** or tell it what to change.
4. **It tests small first,** does the work, and shows you proof.
5. **It teaches you one tip:** "Next time you can say: ...", so you get better every time.

Three modes:

| You type | EUGENE does |
|---|---|
| A task | Plans it, tests it, does it, proves it |
| "explain ..." | Explains AI layers, Claude Code, MCP, API, websites, in plain words |
| "improve this prompt: ..." | Rewrites your prompt and shows what changed |

---

## What EUGENE never does without your yes

- Publish, send messages or emails, delete, post, or spend money.
- Touch real customers. It tests on your own contact or test data first.
- Ask for your passwords, bank details or API keys in the chat. Keys stay in a private `.env` file.
- Mix one client's information with another's.
- Use songs, footage or photos you do not have permission to use.

---

## A word from Eugene

Do not limit your ideas. Give the whole picture to the AI, then study what comes back. Learn the
tools and invest in them, even when it feels like a risk.

> "He which soweth bountifully shall reap also bountifully." 2 Corinthians 9:6 (KJV)

## License

MIT. Free to use and share.
