---
name: pack-for
description: Make a paste-ready copy of this rucksack for an AI app that cannot read it directly (ChatGPT custom instructions, Claude memory or preferences, Meta Muse, Grok, Gemini saved info). Use when the person wants another app to know them, or asks to update a stale copy.
metadata:
  version: 0.3
---

# Pack it for an app

Some apps cannot read a folder or a repository, or can only read it when asked. For those,
the rucksack is the source and the app holds **a copy**. This skill makes the copy. A copy
is one way and goes stale; the date in `FLEET.md` is how the person knows.

1. Ask which app. Read `START.md`, `USER.md`, `SOUL.md` and `LEARN.md`.
2. Every copy carries, in this order and in plain words:
   - **About me**: USER.md In short, what I do, what I want help with.
   - **My boundary**: what never goes in, and what to ask about first.
   - **How to work with me**: the SOUL.md lines.
   - **How I like to learn**: the lines under "How I like to learn" in `START.md`, word for
     word, including the fixed teaching line at the end.
   - **Working on now**: from LEARN.md.
   - **House rules**: the five lines under "House rules" in `START.md`, word for word.
   - **Where my rucksack lives**, only if it is on GitHub and this app has a connector:
     "My context lives in my rucksack, the GitHub repo <owner/repo>. Read START.md before
     answering anything about me." When the app can read the rucksack, this line matters
     more than the rest: it keeps the copy from being the only thing the app knows.
3. Fit the copy to the app's shape and size:
   - **ChatGPT personalisation**: two blocks named by what they hold, about 1,500
     characters each. "About me": About me, My boundary, Working on now. "How to respond":
     How to work with me, How I like to learn, House rules, Where my rucksack lives. The
     app's fields change over time; tell them to put "About me" in whichever field asks
     about them and "How to respond" in whichever asks how ChatGPT should respond. The
     menu is spelt "Personalization" in the app.
   - **Claude**: one block of plain prose for profile preferences or a memory import.
   - **Meta Muse**: `Memory.md` content from About me and Working on now; `Soul.md` content
     from How to work with me, How I like to learn and House rules.
   - **Grok, Gemini saved info, anything else**: one block, as short as the field allows;
     keep the boundary and the house rules whole and cut from About me first.
4. Nothing from `MEMORY.md`, `memory/`, `vault/` or under the boundary goes in a copy.
   A copy is what a stranger app may know.
5. Give the person the copy in a copyable box and say where to paste it in that app, one
   step at a time. If you are not certain where the setting is in the current version of
   the app, say so and tell them to look in the app's settings for "Personalisation",
   "Custom instructions", "Preferences" or "Memory"; never invent a menu path.
6. Getting it to the right device: if the app is on their phone and uses the same account
   as an app on this computer, they can paste it into that app's settings here, because
   settings belong to the account; ask them to check on the phone afterwards. Otherwise
   offer to save the copy as a file in the rucksack (readable on the phone if the folder
   is in their Drive or Dropbox), or they can email it to themselves.
7. Record it: write "a copy" and today's date for that app in `FLEET.md` (directly while
   setting up or during the look-back; otherwise under `## Proposes` in your `memory/`
   note).
