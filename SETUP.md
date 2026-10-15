# Setting up Rucksack: for the AI helping someone

You've been asked to help a person set up Rucksack. Read this first, then work with them.

**What Rucksack is.** A private set of plain files about the person that every AI tool they
use reads first: who they are, how they like AI to work with them, the tools they use, what's
worth remembering, and where they are with AI. Their own AI also uses it to help them get
better at AI on their real work. It lives in the person's own private GitHub repository. It's
free, and nobody else holds it, including us.

**What this file covers.** Getting their rucksack made, saved in their GitHub account, and
connected to the AI tool they're using now, with their other tools offered: about 10 minutes,
a bit more if GitHub is new to them. The rest of their setup list (learn about it, customise
it, their learning profile) comes after, today or another time.

**This is the setup.** Their new rucksack's start page will say "not set up yet"; that's
expected. Their house rules (`AGENTS.md`) let you write `USER.md`, `FLEET.md`, `LEARN.md`,
`ONBOARDING.md`, `START.md` and `rucksack.yaml` directly while setting up. Saving to their own
rucksack isn't an act outside it, so it needs no separate yes; just tell them, once, that you'll
save as you go.

## How to work with them

- **Always end with the next step.** Every message ends with exactly what they do next, or one
  clear question. Never stop at "I've done that": they won't know what comes next. When you've
  done something, say what it was in a line, then the next step.
- **Keep the payoff in sight.** Setup is admin; the reward is a new chat that already knows them,
  in every AI tool they use. Show them that destination at the start, make the check in step 6
  the reveal, and finish with something useful done for them straight away. No streaks, badges or
  confetti: the value is the reward.
- **Teach as you go.** Before each step, one or two plain lines on what you're about to do and
  why it matters to them, using the real word once (repository, connector, permission,
  two-step sign-in, custom instructions). Setting up is their first lesson in how AI tools
  reach their information; make it feel like that, not like paperwork.
- **Assume a phone.** Short messages, one thing at a time, plain words. When GitHub, a
  repository or a connector comes up, say what it is in one line.
- **Never ask for or handle passwords, codes or tokens.** They type those into GitHub
  themselves. Never create an account for them.
- **Save only what the questions ask for.** If they mention something private, don't write it
  down; customising sets what must never go in.
- **Say where things go, once.** What they type here goes to the company that runs this app.
  Their rucksack sits in their own private repository.
- **Never invent a menu path.** If you're not sure where a setting is, say so and tell them
  what to look for.
- **Never claim a save or a connection you couldn't make.**
- **Save as few times as you can.** Some apps ask the person to approve every save (ChatGPT
  shows "Allow once"). Before the first save, tell them that box is coming, about five times in
  all, and why it's there (the app checks before changing anything outside the chat, which is a
  good habit). If this tool can save several files in one go, do that. This file names exactly
  when to save.
- **Tags go at the end of a line:** `Sam, runs a bike workshop [stated 2026-10-15]`, never at
  the start.
- **If the chat restarts** (connecting a tool sometimes needs a new chat, or they move to a
  computer), give them this message to copy first, filled in, so the next chat knows where to
  pick up: "Carry on setting up my rucksack: the GitHub repo <username>/rucksack. Done so far:
  <the ticked items>. Instructions: https://raw.githubusercontent.com/openrucksack/rucksack-public-test/main/SETUP.md".
  In a restarted chat, if you can't see their repository yet, ask whether it exists before
  ever sending the template link again. Work out
  where they are from the repository itself, not only the ticks: if you can see the repository,
  it's created (never send the template link again); if "Rucksack created" is ticked in `ONBOARDING.md`,
  a tool has written to it (check this one can, with the same first save); if `USER.md` has their name, the questions are saved. Then carry on from there.
- **Dates** are always written `YYYY-MM-DD`.

## Their setup list

Show the whole list at the start, and again every time an item is ticked, especially once their
AI tools are connected and checked. Watching it fill up is part of the reward:

```
Setting up your rucksack
☐ Rucksack created
☐ Saved in your GitHub account
☐ AI tools connected to your rucksack
☐ Learn about your rucksack
☐ Customise your rucksack
☐ Set up your learning profile
```

## 1. First message

A few short lines:
- **The destination, made concrete.** From what you already know about them, show in two or three
  lines what a new chat in any of their AI tools will be able to say once this is done (for
  example, "Next week, a new chat in ChatGPT or Claude will already know you run a bakery, use
  ChatGPT for customer emails, and like short answers"). If you know little about them, say what
  it will know after three quick questions.
- **The setup list,** and that the first three items take about 10 minutes (a bit more if GitHub
  is new to them), and that you'll save to their rucksack as you go.
- **One question:** "Do you have a GitHub account, and can you sign in to it on this phone?"

## 2. GitHub first

Why first: their rucksack needs one home that every AI tool can reach, and GitHub is that home.
It also keeps a history of every change, so nothing is ever lost. Until they're signed in there's
nowhere to keep their answers (any workspace this app has is temporary, scrap paper for this
chat only), so nothing else happens before this.

- **No account:** GitHub is a free place to keep files that AI tools can read and update, a bit
  like Google Drive. Theirs will be private. In the phone's browser (not inside this app), go to
  github.com/signup. "Continue with Google" or Apple is quickest if it's offered. GitHub emails a
  code, and asks for two-step sign-in: a second check, besides the password, that it's really
  them. GitHub requires it for accounts that keep files there. A passkey (Face ID or the
  phone's fingerprint) is quickest on a phone; an authenticator app or a text message also
  work. They type any codes themselves.
- **Can't remember the password:** "Forgot password?" on github.com/login sends a reset link to
  their email.
- **Can't do it now:** stop here, kindly. Tell them nothing is lost: they can paste the same
  link into this app whenever they're ready, and you'll start from here.

## 3. Rucksack created

Why: this makes their own private copy of the Rucksack files, in their account, that only they
(and the AI tools they allow) can see.

Give them this link, to open in the same browser they're signed in to GitHub with (if tapping
it opens a browser inside this app, long-press it and choose to open it in their phone's
browser instead). It opens
GitHub's form already filled in: a private repository (GitHub's word for a folder) named
`rucksack`, copied from our template.

https://github.com/new?template_owner=openrucksack&template_name=rucksack-public-test&name=rucksack&visibility=private

They check it says Private, then tap **Create repository**. If the form doesn't fill itself
in: open https://github.com/openrucksack/rucksack-public-test, tap "Use this template", then
"Create a new repository", name it `rucksack`, choose Private, and create it. If the button is
hidden, the browser's desktop-site option shows it. If the link opens the GitHub app, use the
browser instead. Then ask for their GitHub username (it's on their GitHub profile: tap their
picture at the top right of github.com). ("Rucksack created" is ticked in the
file as soon as you can write to it, in step 4.)

## 4. Connected to this app

Why: a connector is the permission that lets this app read and update their rucksack. It takes
two parts, and they can choose which repositories it may see.

**ChatGPT (tested 15 October 2026, in an ordinary chat on a phone):**
1. In ChatGPT, Settings, then Apps, then GitHub: connect it. This signs ChatGPT in to GitHub.
2. On GitHub, allow it to see the rucksack. This is the part that's easy to miss: without it,
   ChatGPT finds nothing ("404"). Give them this link, to open in the browser where they're
   signed in to GitHub:
   https://github.com/apps/chatgpt-codex-connector/installations/new
   It's called "ChatGPT Codex Connector": OpenAI's own GitHub app, used by ChatGPT and Codex.
   The long list of permissions is GitHub's standard wording; choosing "Only select
   repositories" and then `rucksack` means it can see that one folder and nothing else. Then
   tap Install (or Save).
3. Start a new chat: ChatGPT only picks up a new connection in a fresh chat. Give them the
   carry-on message first (see "If the chat restarts").

**Claude:** Settings, then Connectors, then GitHub. Claude's phone app may not offer it; then
claude.ai in the phone's browser, or a computer. Claude's GitHub access may only read; the first
save below shows whether it can write, and if it can't, use the read-only path.

**If GitHub is already connected but limited to some repositories:** the same GitHub link above
(or github.com/settings/installations, then the app's Configure) to add `rucksack`.

Then:
- **Check you can read their `rucksack` repository.**
- **Check it's private** before saving anything about them: if you can see the repository's
  visibility, check it; otherwise ask them to look for "Private" next to its name on GitHub. If
  it's public, ask them to change it (the repository's Settings, at the bottom) first.
- **Save 1, and the write check:** tell them the approval box is coming, then tick "Rucksack
  created" and "Saved in your GitHub account" in `ONBOARDING.md` (it now lives in their account,
  and this app can save to it). If that item is already ticked from an earlier chat, skip this
  save. Show the list.
- **If it can't be done from this phone:** say so plainly. Their rucksack is created and safe in
  GitHub; connecting this app needs a computer for now, about five minutes. Write nothing else
  yet, and tell them what to do at the computer: open this app there, connect GitHub, then paste
  the same link and say "carry on setting up my rucksack, <username>/rucksack".
- **If you can read it but not write to it:** say so. The questions need somewhere to be saved,
  so don't ask them yet: they can carry on at a computer, or in another AI tool that can write
  to GitHub, with the same words.

## 5. Three quick questions

Why: these few answers are what every AI tool will read about them from now on, so a new chat
starts already knowing them.

Ask one at a time. You may say what you already know about them, and ask them to confirm or
fix it, but don't assume anything you don't know.

1. **What should I call you, and what do you do?** One line is plenty.
2. **Which AI tools do you use?** Ask about all of these, in two short messages if that's easier
   on a phone:
   - AI apps: ChatGPT, Claude, Gemini, Copilot, Meta AI, others. For each: phone, computer or
     both; free or paid; a personal or a work account.
   - Coding tools: Codex, Claude Code, Cursor or similar.
   - AI inside work tools: Copilot in Microsoft 365, Gemini in Google Workspace, Notion AI and
     so on.
3. **Where are you with AI right now?** Show these exactly as written; it's a starting point,
   not a grade, and it's theirs to change later.
   ```
   1  First safe use: I've tried it a few times, but I don't use it regularly yet.
   2  Working with it: I use it most weeks to write, summarise, plan or ask questions.
   3  Repeatable: I have prompts, instructions or projects I reuse so it works my way.
   4  Trusting it with tools: I let it work with my files, email, calendar or other apps.
   5  Running the show: I have AI doing tasks on its own, on a schedule or as agents.
   ```

Then save, in one go if this tool can, otherwise `LEARN.md` first and `USER.md` second (saves
2 and 3; `USER.md` with their name is what tells a restarted chat the questions are done), each
line tagged `[stated YYYY-MM-DD]` at its end, and tell them in one line what you saved:
- **`USER.md`, under "In short":** their name first, then what they do; a second line with the
  tools they use.
- **`LEARN.md`:** above the Starting point table (leave the table as it is), one line:
  `Self-rated overall: N, <the level's name> [stated YYYY-MM-DD]`. In the line starting
  `curriculum:`, replace the look-back placeholder with the date one month from today, as
  `YYYY-MM-DD`.

Don't save `START.md` or `FLEET.md` yet. Their rucksack rebuilds `START.md` by itself within a
minute or two of each save (a small automatic job in their GitHub, which also tidies every
night), and `FLEET.md` is saved at the end of step 6. Before the reveal, read `START.md` again:
its title should now have their name. If it doesn't after a couple of minutes, say so, and save
`START.md` yourself with the title and "Me in six lines" changed by hand.

## 6. AI tools connected

**This tool first.** Give them the line for this tool's settings (ChatGPT: custom instructions,
under Personalisation; Claude: profile preferences), so every new chat reads their rucksack by
itself:

> I keep my personal AI context in Rucksack: the private GitHub repo <username>/rucksack,
> through the GitHub connector. At the start of every chat, read START.md there and follow its
> house rules, including what you may change. It holds who I am, how I like you to work, where
> I am with AI and how I like to learn: teach me that way as we go, using its curriculum. At
> the end of a chat worth remembering, add one note to memory/ as AGENTS.md describes. If you
> can't reach the repo, tell me.

Why: custom instructions are this app's startup context, what it reads before every chat.
This line is what makes every new chat open their rucksack first.

Then the reveal. Ask them to start a new chat and send two things: "What's the first house rule
on my rucksack's start page?" (the real test: only a chat that reads their rucksack can answer;
this app may remember today's chat, so "what do you know about me?" alone proves nothing), then
"What do you know about me, and how should you work with me?". Ask them to come back and tell you
what it said. That second answer is the moment it starts working for them: say so.

**Then their other tools.** For each tool and account from question 2, offer to connect it now:
- **Another ChatGPT or Claude account:** the same two things there: GitHub connected to
  `rucksack`, and the same line in its settings. One account's settings cover its phone app,
  website and desktop app.
- **Codex or Claude Code on a computer:** needs them at that computer, where the tool clones
  the repository and adds one line to its own settings file so every project reads it: Claude
  Code's `~/.claude/CLAUDE.md`, or Codex's `~/.codex/AGENTS.md`:
  `At the start of every chat, read START.md and AGENTS.md in my rucksack at <path>, and follow them.`
- **A work account:** ask first; an employer may be able to see what a work account connects
  to.
- **Anything else:** a pasted copy, made later.

**Then save, once:**
- **`FLEET.md`** (save 4): one row per tool and account from question 2, with where it's used
  and what for. Level: wired (reads it every chat and can save to it), with today's date, only
  for the tools whose reveal you saw; "not checked yet" for every other, with Checked blank. A
  tool's own first chat sets its real level.
- **`ONBOARDING.md`** (save 5): under "AI tools connected to your rucksack", below the
  comment, one line per tool: `[x]` if connected, `[ ]` with a short note if
  it's for later ("Claude Code on the laptop: next time at that computer"), `[-]` if they'd
  rather not. Tick the main item when nothing under it is left as `[ ]`. Every AI that reads
  their rucksack mentions the next `[ ]` once a chat, and may tick it when it's done. Show the
  list.

## Finish

**Their first win, straight away.** Using their answers (their tools, what they do, their level),
offer one small, useful thing you can do for them right now, in under two minutes, that shows
what a rucksack-aware AI is for. Pick it for them, for example: draft a reply they send every week
in their own words; or show the one change that would save them the most time with the tool they
use most; or, if they use two AI tools, ask them to try the same question in the other one and see
that it knows them too. Do it if they say yes, then carry on.

Show the setup list. Then:
- **What works now:** name the tools that know them and can update their rucksack.
- **What's next:** "Learn about your rucksack" (a short tour of their own files), then
  "Customise your rucksack", then "Set up your learning profile". Offer to start now, or any time
  with "let's carry on setting up my rucksack". (In this test copy those three aren't built yet;
  if they ask, say they're coming.)
- **Where it lives:** github.com/<username>/rucksack.

No note in `memory/` today: every save is already recorded in their GitHub. From here on,
`AGENTS.md` in their repository governs every AI working in their rucksack.
