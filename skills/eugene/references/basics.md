# The basics, in plain words

Explain only what the user asks. One everyday example each.

## The three layers of AI

```
  3  AGENTIC AI        It does the work.        Claude Code, with skills and MCPs
  2  AI AUTOMATION     It runs 24/7 on rules.   Workflows, reminders, follow-up texts
  1  AI CHAT           It answers.              ChatGPT, Claude chat
```

- **Layer 1, AI chat.** You ask, it answers, and then YOU copy, paste and do the work by hand.
  Example: you ask how to write a follow-up text, it writes one, you send it yourself.
- **Layer 2, AI automation.** A rule you set once runs by itself, day and night.
  Example: when someone books a call, a reminder text goes out one day before. It follows the rule
  exactly, but it cannot think about a new situation.
- **Layer 3, agentic AI.** You give a goal, and the AI plans the steps, uses the tools, checks the
  result, and asks you before anything risky.
  Example: "New leads are not getting the welcome text, find out why and fix it." Claude Code reads
  the workflow, finds the cause, tests on your contact, and asks before publishing.

The lesson: most people stay at layer 1. Claude Code works at layer 3, so the repetitive work for
your clients can be done for you, every day.

## What Claude Code is

Claude made by Anthropic, working on your own computer. It can read and write files, run tools,
open websites, and connect to apps. You talk to it in normal words. It needs a paid Claude plan
(Pro or higher).

## What a skill is

A saved set of instructions Claude follows for one kind of job, like a recipe card. EUGENE is a
skill: type `/eugene` and Claude follows Eugene's way of working.

## API

**A key to one service.** A program uses it to ask a service to do something directly, without you
clicking in the app. Example: a voice API turns text into a voice recording; a video API generates a
video clip. APIs often cost money per use, and the key must stay private (in a `.env` file, never in
chat).

## MCP (Model Context Protocol)

**A plug that connects Claude to an app**, so Claude can use that app for you. One plug per app.

```
                 Chrome DevTools
                       |
   Google Drive --- CLAUDE --- GoHighLevel
                       |
                Claude in Chrome
```

The two basic ones to start with:
- **Chrome DevTools MCP:** Claude opens websites in a browser, tests them, takes screenshots and
  measures problems. Good for checking a landing page on a phone size.
- **Claude in Chrome:** Claude uses your real Chrome, with your own logins, and asks before clicking
  anything important. Good for tasks inside web apps.

Ask EUGENE to guide you through setting one up; the exact steps change over time, so let Claude
check the current instructions.

**API vs MCP in one line:** an API is the key to a service; an MCP is the ready-made plug that lets
Claude use it without you writing code.

## Website vs landing page vs funnel

- **Website:** a whole house with many rooms. Home, About, Services, Contact.
- **Landing page:** one door with one offer and one button. Made for an ad or a campaign, so the
  visitor does one thing: book, buy, or sign up.
- **Funnel:** a hallway of pages in order. Landing page, then form, then thank-you page, then the
  follow-up messages.

## Vibe coding

Building apps or pages by describing what you want in normal words while Claude writes the code.
You still check the result: open it, click it, test it on a phone.

## Why people get stuck with AI

They give it one line and expect magic, or they keep their best ideas to themselves. Give the
whole picture: the goal, who it is for, what you already have, and your limits. Then let it think
first, test small, and show you proof.
