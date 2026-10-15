---
name: setup
description: Set up a new rucksack with the person, about 20 minutes, ending with every AI app they use wired to it. Use when USER.md has no answers yet, or when the person asks to set up, start again, or wire another app.
metadata:
  version: 0.8
---

# Setting up a rucksack

Read `AGENTS.md` first: its rules bind you. You are the person's own AI, in whatever app
they opened this in. There is no other character; do not invent one or give yourself a name.

Setting up has one job: the person leaves with a working rucksack that **every AI app they
use can reach**, has seen it work, and knows how it improves as they go. A folder they never
open again is a failure, so the last step, wiring their apps, matters as much as the first.
No other task and no primer.

About 20 minutes, five steps. Keep it moving and keep it visual:

- **Short messages.** A few lines, then one question.
- **Show progress.** Start each step with its line from the map, for example
  `**② About you** · step 2 of 5`.
- **Every answer packs something.** Write each answer into its file straight away and show
  the folder growing (`USER.md ✅`). The questions should feel like packing, not a form.
- **Offer choices with letters**, and always accept their own words instead.
- **Show, do not describe.** Plain-text pictures (the folder, the bars) and the dashboard
  (`view.html`) do the explaining.
- **Assume they know things.** They already use AI. Ask before explaining something they
  may know; use the real AI words and say what each means the first time. Short answers:
  combine questions. Never more than about eight prompts before they see their folder
  filling.
- **When a step needs them** (a click, a setting, a decision), say exactly where and what.
  Never ask them to type a command; if one needs running, you run it and say a box may ask
  them to allow it.

## ① What this is (one message)

One message of five short lines, the map, then "Ready?". Nothing else first.

- This folder, `rucksack`, holds plain files about you: who you are, how you use AI, how you
  like it to work with you, what stays private. Any AI app that reads it knows you, and the
  files are yours, not locked inside one app.
- It also makes me a better teacher: it keeps where you are with AI and how you like to
  learn, so I can suggest the next useful thing on your real work, and once a month, if you
  want, look back at how you've been using AI.
- Today we fill it in, see it work, then connect it to every AI app you use, so you never
  have to come back to this folder to use it.
- What you type goes to the company that runs this app, like any chat. I work only with the
  files in this folder, and I will ask before touching anything else.
- Today:

```
Today, about 20 minutes
① What this is   ② About you   ③ Your rucksack   ④ See it work   ⑤ Wire your apps
```

If they are worried about other files on the computer (client records, anything private),
say only what you control: "I won't open, read or change anything outside this folder
without asking you first." Do not claim what the app can or cannot see unless you know.

## ② About you (seven questions, packing as you go)

The first time you save, say: "Your app may ask permission to save in this folder. If a
box appears, it only means that." Then after each answer, write it and show the folder
line that changed. Every line you write about them carries the date and a tag, as
`AGENTS.md` says: `[stated 2026-10-14]` for what they told you.

1. **You.** What should I call you, and what do you do for work?
   Write USER.md: In short (their name first), What I do. Show `USER.md ✅ <name> · <work>`.
2. **Your apps.** Which AI apps do you use, where, and for what? Offer
   `a ChatGPT  b Claude  c Gemini  d Copilot  e Meta AI  f Grok  g inside a work tool  h other`
   then phone, computer or both; free or paid if they know; what they use it for at work
   and at home; how often. Write FLEET.md: one row per app **per place** (ChatGPT on the
   phone and the ChatGPT app on this computer are two rows). Leave Level blank for now;
   step ⑤ fills it. Add their uses to USER.md. Show `FLEET.md ✅ <apps>`.
3. **What you have done with it.** Always ask it; it sets the starting point. One message,
   answer with letters or words:
   ```
   a  asked it a question, or had it write something
   b  given it a document or photo to work with
   c  asked two different AIs the same thing and compared
   d  checked what it said against a proper source
   e  told it standing instructions, so it remembers how you like things
   f  let it work with files on your computer
   g  connected it to your email, calendar or drive
   h  made something it can reuse, like a template, a custom GPT or a skill
   i  had it do something on a schedule without you
   ```
   Write the Starting point table in LEARN.md (rules below). Show the bars.
4. **What you want.** What would you most like AI to help you with, or get better at, this
   month? Write it to USER.md. Then choose "Working on now" (one activity) and "Next" (two)
   in LEARN.md from the exercise table in `.curriculum/exercises/README.md` (levels 1 and 2),
   picking what fits their answer. Write each as a plain line any app can act on without the
   curriculum, ending with its file: `Turn a vague ask into a clear one, on a real email
   (about 15 minutes; .curriculum/exercises/E02.md)`. Show `LEARN.md ✅ working on: <activity>`.
5. **Your boundary.** Anything that must never go in your rucksack or our chats, and
   anything you want me to ask about first? One line on why: every AI that reads it sees
   it, so it should hold only what you are happy for all of them to see. Common choices:
   other people's details, money and account information, health, confidential work. If a
   word is broad ("financial"), one quick follow-up is fine ("does that include client
   budgets?"). Their call; do not argue. Write USER.md My boundary and "Ask me first
   before". This earns Staying safe level 1: record it under Level earned.
6. **How I should work with you.** `a short and straight to the point  b detailed  c somewhere
   in between`, and plain or technical if they care. Write it as the **first** bullet of
   SOUL.md, above the starter lines. Show `SOUL.md ✅ <their answer>`.
7. **How you like to learn.** Pick any that fit, or say it your way:
   ```
   a  a quick idea as we go, then back to the task
   b  explain the why, not just the how
   c  show me an example first
   d  quiz me now and then
   e  give me something to try on my own work
   f  leave it unless I ask
   ```
   Write their answer, in their words, under "How I like to learn" in LEARN.md. Show
   `LEARN.md ✅ learns by: <answer>`. Say in one line that every AI reading the rucksack
   will follow it, and they can change it any time.

If they name a real person, business or amount before the boundary exists, say in one line
that it has gone to the AI company as chat, that you will not write it down, and carry on.

## ③ Your rucksack (one picture, one check)

Show the whole folder and their starting point together, filled with their own details.
The shape:

```
your rucksack
├── USER.md      ✅ <name> · <work> · <what they want>
├── SOUL.md      ✅ <how to work with them>
├── FLEET.md     ✅ <apps and where>
├── LEARN.md     ✅ working on: <activity> · learns by: <answer>
├── memory/      ·  a short note after a chat worth remembering
├── skills/      ·  things you teach your AI to do
├── projects/    ·  what you are building
├── try/         ·  a scratch area for trying things
└── vault/       🔒 real documents, never leaves this computer

Choosing            ▰▰▱▱▱  starting at 2
Asking              ▰▱▱▱▱  starting at 1
Checking            ▰▱▱▱▱  starting at 1
Staying safe        ▰▱▱▱▱  earned today: you set a boundary
Keeping it running  ▱▱▱▱▱
Growing             ▱▱▱▱▱
```

One line on what each ticked file is for. The bars are what you told me, not a grade; they
only move when you do something and see it work. Then once: "Anything wrong?"

### Starting point from question 3

Self-reported, in LEARN.md's Starting point table, dated.

| Area | Starting point |
|---|---|
| Choosing | 1 if a; 2 if also c |
| Asking | 1 if a; 2 if also e or h |
| Checking | 1 if c or d; 2 if c and d |
| Staying safe | 1, earned in question 5 (also under Level earned) |
| Keeping it running | 1 if e; 2 if f or h; 3 if i and h |
| Growing | blank; this one shows over time |

## ④ See it work

1. Run the tidy: `scripts/tidy.py` if you can run scripts (the app may ask to allow a
   command; say so first), otherwise steps 2 and 7 of `skills/teach/references/tidy.md` by
   hand. It builds `START.md` and the dashboard, `view.html`.
2. Show the dashboard: "Your rucksack as a page is the file `view.html` in the rucksack
   folder; double-click it to open it in your browser." If they are not sure where the
   folder is, offer to open it for them (one command; say a box may ask). If you cannot
   run commands, paste the main parts of `START.md` instead.
3. The test: "Start a new chat in this app, in this same folder, and ask: *What do you know
   about me, and how should you work with me?*" Help them find "new chat" only with what
   you know for certain about this app; otherwise say "look for New chat or a + button".
   Wait for them to come back. If it got something wrong, fix the line together: their
   first real edit.
4. If the test passed and they saw it: Keeping it running level 1, under Level earned,
   dated.

## ⑤ Wire your apps

The point of a rucksack is that it is in every chat, in every app, without them coming back
here. Go through FLEET.md one app at a time and get each to the best level that app allows.
Say the level honestly as you go; never claim more than the app does.

**First, where does this rucksack live?** Check whether this folder is a git repository with
a GitHub remote (`git remote -v`, or ask them if you cannot run commands). Write the answer
into `rucksack.yaml` as `tier: git` or `tier: folder`, and note `<owner/repo>` from the remote
if there is one.

**If it is on GitHub, save what you've packed there before wiring any phone app**, or the
phone will read the empty template. Say what and where in one line ("This sends your
rucksack's files to your private GitHub copy, <owner/repo>"), wait for their yes, run the
tidy, then commit everything except `vault/` and push to the default branch. If you cannot
run git, tell them exactly what to do in their app, and wait until it is done.

| Level | Means |
|---|---|
| **wired** | the app reads the rucksack at the start of every chat, and can write back |
| **connected** | the app reads it when asked, through a connector, and may write back |
| **a copy** | the app holds a pasted copy of the essentials, which goes stale |

**Apps on this computer that open folders** (Claude Code, the ChatGPT desktop app's Codex
mode, Claude's Cowork). They read the rucksack when opened in this folder. To make them read
it in every project and folder, offer one line in the app's own personal instructions file:
Claude Code reads `~/.claude/CLAUDE.md` in every project; the ChatGPT desktop app's Codex
mode reads `~/.codex/AGENTS.md`. The line: `At the start of every chat, read START.md and
AGENTS.md in my rucksack at <full path>, and follow them.` This touches a file outside the
rucksack, so say what and where and wait for a yes. If the app cannot do this, say so.
Level: wired.

**Chat apps on the phone or the web** (ChatGPT, Claude) when the rucksack is on GitHub:
1. Connect GitHub to the app **on a computer, in the web version** (chatgpt.com or
   claude.ai). On 14 October 2026 neither phone app offered the choice of organisation or
   repository. Find the setting with what you know for certain about the app ("Settings,
   then Connectors or Apps"); never invent a menu path. They must allow the app to see this
   one repository.
2. Add a standing instruction where the app keeps instructions about them (ChatGPT: custom
   instructions; Claude: profile preferences):
   `My context lives in my rucksack, the GitHub repo <owner/repo>. Read START.md before
   answering anything about me, and follow its house rules.`
3. Test it on the phone: a new chat, "What do you know about me?". If it answers from the
   rucksack, the level is connected (ChatGPT read it unprompted with this instruction in a
   test on 14 October 2026; Claude's equivalent was not yet tested). Both apps wrote a note
   back through the connector in that test.

**Everything else**, and any app where the steps above fail: make a copy with
`skills/pack-for/SKILL.md` and paste it in. Level: a copy, with the date.

When the rucksack is only a folder (no GitHub yet), phone apps get a copy. Say in one line
what GitHub would add (phones read and write it, and a nightly tidy runs) and offer it as a
next activity, not now.

Write each app's level and today's date into FLEET.md directly, then show the fleet:

```
your apps
ChatGPT (phone)    connected   2026-10-14
ChatGPT (laptop)   wired       2026-10-14
Claude (phone)     a copy      2026-10-14
```

## Then: how it works from here (three short lines, then the close)

1. **Working with it**: every ordinary chat in those apps already knows you. When something
   is worth keeping, the AI leaves a note in the rucksack, or, where it cannot write, ends
   with *For your rucksack:* and the line to keep.
2. **Getting better as you go**: the AI will offer one idea at a time, the way you said you
   like to learn, and "what should I try next?" works in any of those apps. Name the
   "Working on now" activity and the two in "Next", one line each, with roughly how long.
3. **Once a month**, if they want: the look-back, which also asks each app what it remembers
   about them and brings the month back into the rucksack. Write today's date plus one month
   into the `next look-back due:` place on LEARN.md's first line, so every app can see when
   it is due. Offer to put a 20-minute entry in their calendar, or tell them what to put in.

Then:

- **Pilot only** (`rucksack.yaml` says `pilot: true`): ask once about short progress
  reports. They read every one first; nothing under their boundary is ever in one; they
  can stop any time.
- **Write the one note** for this chat in `memory/` (`## Did`, `## Decided`, `## Remember`,
  `## Proposes`, `## Flags`, with `feedback` under Flags if they said yes to reports), then
  run the tidy once more. If the rucksack is on GitHub, commit and push again (the yes from
  step ⑤ covers this one follow-up). If a report was made, show it and offer a ready email to
  `pilot_contact`.
- **Offer the real thing.** "If you have 15 minutes, we can do <their Working on now
  activity> now, in whichever app you like." If they say yes, carry on with
  `skills/teach/SKILL.md`.

## If they question the point

Answer in two lines tied to what they want (from question 4 if you have it), then bring the
proof forward: pack what you have, run step ④, and come back to the remaining questions.
If, after seeing it, they do not want it, that is their decision; help with whatever they
came for.

## Not while setting up

- No task before the wiring is done; the real task is offered at the end.
- No levels from answers. Starting point only; earned levels only for the boundary and a
  passed test.
- No routines. Offer them as later activities.
- No privacy lecture. One line on why the boundary matters, then their choice.
