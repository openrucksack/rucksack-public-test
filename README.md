# Your rucksack

A rucksack is your own AI context: who you are, how you want AI to work with you, the apps
you use, what you are working on, and how you like to learn. Every AI app you connect reads
it and knows you. It also makes your AI a better teacher: it keeps where you are with AI, so
whichever app you use can suggest the next useful thing on your real work, and once a month,
if you want, look back at how you have been using AI. You own all of it, in plain text you
can read, and you take it with you when you change apps.

There is no extra app and no extra AI. The rucksack works through the AI apps you already
use; the instructions inside it (the house rules in `AGENTS.md` and the skills in
`skills/`) are files you can open and read.

What you type, and any file an AI reads, goes to the company whose app you are using,
under their privacy settings. The rucksack holds only what you are happy for every AI
you connect to see, and setting up asks what must never go in before anything else.

If the GitHub account or the computer was given to you by an employer, whoever
administers it may be able to read the rucksack, and keeps it if you leave. Put your
rucksack on an account you own.

## Setting up (about 10 minutes, on your phone or a computer)

Paste this into ChatGPT or Claude, and your AI walks you through it:

> I'd like to set up Rucksack. Read https://raw.githubusercontent.com/openrucksack/rucksack-public-test/main/SETUP.md and help me through it.

You'll need a free GitHub account (it can help you make one). Your rucksack is made in your
account, connected to the AI tools you use, and your setup list is kept in `ONBOARDING.md`.

## Using it

You don't come back to this folder to use it. Once your apps are connected, every chat in
them already knows you. Each app is at one of three levels, shown on your dashboard:

| Level | What it means |
|---|---|
| **Wired** | Reads your rucksack at the start of every chat, and writes notes back |
| **Connected** | Reads it when asked, through a connector, and may write back |
| **A copy** | Holds a pasted copy of the essentials, which goes stale |

On a computer, Claude Code and the ChatGPT desktop app can be wired. On a phone, ChatGPT and
Claude can read and write your rucksack through their GitHub connectors; connect GitHub in
the web version on a computer first (the phone apps did not offer it when we checked, on
14 October 2026). Everything else gets a copy: ask any AI that can read your rucksack to
"pack it for" that app.

When something is worth keeping, your AI leaves a note in `memory/`. Where an app cannot
write, it ends with *For your rucksack:* and the line to keep.

Ask any of them "what should I try next?" whenever you like. Once a month, the look-back
also asks each app what it remembers about you and brings the month back in.

## What is in here

- `START.md`: the one page every AI reads first. `view.html`: your dashboard; double-click
  it. Both are generated; edit the files they come from.
- `USER.md`: about you. `SOUL.md`: how you want your AI to work with you.
- `MEMORY.md`: durable things worth remembering. `memory/`: the notes your AIs leave.
- `FLEET.md`: your apps and how each reaches the rucksack. `HEARTBEAT.md`: routines.
- `LEARN.md` and `learn/`: where you are with AI, how you like to learn, and what is next.
- `skills/`: things you have taught your AI to do, plus three that came with the rucksack:
  `setup`, `teach` and `pack-for`.
- `projects/`: what you are building with AI right now. `try/`: a scratch area.
- `vault/`: real documents, local only, never shared, never in git.
- `AGENTS.md`: the house rules every AI follows in here.

## Pilot feedback

<!-- Pilot only. Remove when the pilot ends. -->
This is a pilot. If you said yes to progress reports, your AI drafts a short one from
your notes into `feedback/` and shows it to you. Nothing is sent automatically. If you
are happy with it, it gives you a ready-made email to the pilot inbox in
`rucksack.yaml`: one tap to send, or ignore it. If anything is confusing, wrong
or broken, that is the most useful thing you can tell us.

## Costs

The rucksack is free and open. The AI apps have their own plans; free plans go a long
way, and your AI says when a step genuinely needs a paid plan and what the alternative
is.

## Credits

The file names and the memory layout follow OpenClaw's workspace, which Meta Muse and
NVIDIA NemoClaw also use, so those agents read a rucksack unchanged. Skills follow the
Agent Skills standard. The idea of tagging every fact as stated, observed or inferred is
from memory-passport. The curriculum draws on the OECD and European Commission AI
literacy framework (CC BY 4.0).
