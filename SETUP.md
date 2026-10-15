# Setting up Rucksack: for the AI helping someone

You've been asked to help a person set up Rucksack. Read this first, then work with them.

**What Rucksack is.** A private set of plain files about the person that every AI app they
use reads first: who they are, how they like AI to work with them, the apps they use, what's
worth remembering, and where they are with AI. Their own AI also uses it to help them get
better at AI on their real work. It lives in the person's own private GitHub repository. It's
free, and nobody else holds it, including us.

**Today is part 1 of 2.** Today (about 15 minutes, a bit more if GitHub is new to them, on a
phone or a computer): make their rucksack and connect it to the AI apps they use, so they
never have to come back to one device to use it. Part 2 is a separate sitting: a short tour,
and making it theirs (what must never go in, how they like AI to work with them, how they
like to learn). Don't start part 2 today.

**This file replaces `skills/setup/SKILL.md` for today.** Their new rucksack's start page will
say "not set up yet: follow skills/setup"; that's expected, ignore it. Today counts as setting
up, so you may write `USER.md`, `FLEET.md`, `LEARN.md`, `START.md` and `rucksack.yaml`
directly. Tell them once, at the start, that you'll save to their rucksack as you go; their
yes covers today's saves.

## How to work with them

- **Assume a phone.** Short messages, one thing at a time, plain words. When GitHub, a
  repository or a connector comes up, say what it is in one line.
- **Never ask for or handle passwords, codes or tokens.** They type those into GitHub
  themselves. Never create an account for them.
- **Save only what today's three questions ask for.** If they mention something private,
  don't write it down; part 2 sets what must never go in.
- **Say where things go, once.** What they type here goes to the company that runs this app.
  Their rucksack sits in their own private repository.
- **Never invent a menu path.** If you're not sure where a setting is in this app, say so and
  tell them what to look for.
- **Never claim a save or a connection you couldn't make.** If a step fails, say what failed
  and offer the simplest way round it.
- **If the chat restarts** (connecting an app sometimes needs a new chat), they can say "carry
  on setting up my rucksack, <username>/rucksack". Check what's already in their repository
  and carry on from the first unticked item.

The checklist. Show it in full at the start and at the finish; in between, a one-line
"✅ 3 of 6" is enough.

```
Setting up your rucksack
☐ 1 A GitHub account
☐ 2 Your rucksack (your own private copy)
☐ 3 This app connected to it
☐ 4 Three quick questions, saved
☐ 5 Checked in a new chat
☐ 6 Your other AI apps connected
```

## Your first message

A few short lines: what Rucksack will do for them (lead with that), about how long it takes,
that you'll save to their rucksack as you go, the checklist, and one question: "Do you already
have a GitHub account?" Wait for their answer.

## 1. A GitHub account

If they have one, tick it. If not: GitHub is a free place to keep files that AI apps can read
and update, a bit like Google Drive. Their rucksack will be private there. Walk them through
it:
- In the phone's browser (not inside this app), go to github.com/signup. "Continue with
  Google" or Apple is the quickest, if it's offered.
- GitHub may email a code and ask them to set up a second sign-in step (an authenticator app,
  a text message or a passkey). They type those themselves; let them choose.
- Wait until they're signed in.

## 2. Their rucksack

Give them this link, and say to open it in the same browser they're signed in to GitHub with.
It opens GitHub's form already filled in: a private repository (GitHub's word for a folder)
named `rucksack`, copied from our template.

https://github.com/new?template_owner=openrucksack&template_name=rucksack-public-test&name=rucksack&visibility=private

They check it says Private, then tap **Create repository**. If the form doesn't fill itself
in: open https://github.com/openrucksack/rucksack-public-test, tap "Use this template", then
"Create a new repository", name it `rucksack`, choose Private, and create it. If the button is
hidden on a phone, the browser's desktop-site option shows it. If the link opens the GitHub
app instead, use the browser.

Ask for their GitHub username.

## 3. This app, connected

Check whether you can read their `rucksack` repository.

- **If you can't:** tell them how to connect GitHub to this app and allow the `rucksack`
  repository: in ChatGPT, look under Settings, then Apps; in Claude, under Connectors. If the
  phone app won't let them choose the repository, try the same settings in the web version
  (chatgpt.com or claude.ai) opened in the phone's browser. If GitHub is already connected
  but limited to some repositories, the fix is on GitHub: github.com/settings/installations,
  then the app's Configure, then add `rucksack`. A new connection may only show up in a new
  chat (see "If the chat restarts").
- **Then check you can write:** save `tier: git` in `rucksack.yaml`. If you can only read, say
  so now, before the questions: the saves will need another app or a computer.
- **If this app can't reach GitHub at all,** say so plainly: they can finish in another app
  that can, or on a computer.

## 4. Three quick questions, saved

Ask one at a time:

1. **What should I call you, and what do you do?** One line is plenty.
2. **Where are you with AI right now?** Pick the closest; it's a starting point, not a grade.
   ```
   1  I've tried it a few times
   2  I use it most weeks, for writing and questions
   3  I have prompts or instructions I reuse
   4  I let it work with my files or other apps
   5  I have things it runs on its own
   ```
3. **Which AI apps do you use, on which devices, and for what?** For example, ChatGPT on my
   phone for quick questions, Claude on my work laptop. If an app is on a work account, ask
   whether they want their rucksack connected to it; an employer may be able to see what a
   work account connects to.

Then save, each line dated and tagged `[stated YYYY-MM-DD]`, and tell them in one line what
you saved:
- **`USER.md`, under "In short":** their name first, then what they do; a second line with
  the apps they use.
- **`FLEET.md`:** one row per app per device, with what it's for. Leave Level and Checked
  blank until step 6.
- **`LEARN.md`:** above the Starting point table (leave the table as it is), one line:
  `Self-rated overall: N [stated YYYY-MM-DD]`. In the first line, replace the look-back
  placeholder with a date one month from today.
- **`START.md`:** change only two things: the title becomes "<Name>'s rucksack (generated
  <today>)", and "Me in six lines" gets the lines you wrote in `USER.md`. A nightly job
  rebuilds it properly after today.

## 5. Checked in a new chat

First make this app read the rucksack by itself (below, for this app). Then ask them to start
a new chat in this app and send "What do you know about me?", and come back with what it said.
When it answers from the rucksack, tick 3 and 5.

## 6. Their other AI apps

Sort by account, not device: one ChatGPT account's settings cover its phone app, the website
and the desktop app.

- **ChatGPT:** GitHub connected to `rucksack`, and this line in custom instructions (look
  under Personalisation), so a new chat reads it by itself:
  `My context lives in my rucksack, the GitHub repo <username>/rucksack. Read START.md before answering anything about me, and follow its house rules.`
  Level: connected.
- **Claude:** GitHub connected to `rucksack`, and the same line in its profile preferences.
  Level: connected.
- **Claude Code or Codex on a computer:** these read it in every chat, but need the person at
  that computer. Add "next time at your computer: <app>" to what's left; part 2 does it.
- **Anything else (Gemini, Copilot and so on):** a pasted copy, made in part 2.

Record in `FLEET.md` only what is true now: connected and today's date for the apps you
connected; "copy not made yet" or "at your computer" for the rest, with Checked left blank.

## Finish

Show the checklist. If anything is left (a computer app, a copy), say so as one short line.
Then:
- **What they have now:** the apps you connected know them, and remember through their
  rucksack. Name those apps.
- **Part 2:** a short tour, and making it theirs. They can start it any time, in any of those
  apps: "let's do part 2 of my rucksack". (In this test copy, part 2 isn't built yet; if
  they ask, say it's coming.)
- **Where it lives:** github.com/<username>/rucksack.

Then leave a note in `memory/`, as `AGENTS.md` in their repository describes. From here on,
that `AGENTS.md` is what governs every AI working in their rucksack.
