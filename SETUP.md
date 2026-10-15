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
- **If the chat restarts** (connecting a tool sometimes needs a new chat, or they move to a
  computer), they can say "carry on setting up my rucksack, <username>/rucksack". Work out
  where they are from the repository itself, not only the ticks: if you can see the repository,
  it's created (never send the template link again); if `rucksack.yaml` says `tier: git`, this
  tool can write; if `USER.md` has their name, the questions are saved. Then carry on from there.
- **Dates** are always written `YYYY-MM-DD`.

## Their setup list

Show it at the start and the finish, filled in as you go:

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

A few short lines: what Rucksack will do for them (lead with that), the setup list, about how
long the first three take, that you'll save to their rucksack as you go, and one question: "Do
you have a GitHub account, and can you sign in to it on this phone?" Wait for their answer.

## 2. GitHub first

Nothing else happens until they're signed in to GitHub: there's nowhere to keep their answers
without it. (Any workspace this app has is temporary, scrap paper for this chat only.)

- **No account:** GitHub is a free place to keep files that AI tools can read and update, a bit
  like Google Drive. Theirs will be private. In the phone's browser (not inside this app), go to
  github.com/signup. "Continue with Google" or Apple is quickest if it's offered. GitHub may
  email a code and ask for a second sign-in step (an authenticator app, a text message or a
  passkey); they type those themselves.
- **Can't remember the password:** "Forgot password?" on github.com/login sends a reset link to
  their email.
- **Can't do it now:** stop here, kindly. Tell them nothing is lost: they can paste the same
  link into this app whenever they're ready, and you'll start from here.

## 3. Rucksack created

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
browser instead. Then ask for their GitHub username. ("Rucksack created" is ticked in the
file as soon as you can write to it, in step 4.)

## 4. Connected to this app

Connect GitHub to the tool they're using now, so you can read and write their rucksack.

- **Check whether you can read their `rucksack` repository.** If not, tell them how to connect
  GitHub to this app and allow that repository: in ChatGPT, look under Settings, then Apps; in
  Claude, under Connectors. If GitHub is connected but limited to some repositories, the fix is
  on GitHub: github.com/settings/installations, then this app's Configure, then add
  `rucksack`. If the phone app won't let them choose the repository, try the same settings in
  the web version (chatgpt.com or claude.ai) in the phone's browser. A new connection may only
  show up in a new chat (see "If the chat restarts").
- **Check it's private** before saving anything about them: if you can see the repository's
  visibility, check it; otherwise ask them to look for "Private" next to its name on GitHub. If
  it's public, ask them to change it (the repository's Settings, at the bottom) first.
- **Check you can write:** save `tier: git` in `rucksack.yaml`, then tick "Rucksack created" in
  `ONBOARDING.md`.
- **If it can't be done from this phone:** say so plainly. Their rucksack is created and safe in
  GitHub; connecting this app needs a computer for now, about five minutes. Write nothing else
  yet, and tell them what to do at the computer: open this app there, connect GitHub, then paste
  the same link and say "carry on setting up my rucksack, <username>/rucksack".
- **If you can read it but not write to it:** say so. The questions need somewhere to be saved,
  so don't ask them yet: they can carry on at a computer, or in another AI tool that can write
  to GitHub, with the same words.

## 5. Three quick questions

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
3. **Where are you with AI right now?** Pick the closest; it's a starting point, not a grade.
   ```
   1  I've tried it a few times
   2  I use it most weeks, for writing and questions
   3  I have prompts or instructions I reuse
   4  I let it work with my files or other apps
   5  I have things it runs on its own
   ```

Then save, each line dated and tagged `[stated YYYY-MM-DD]`, and tell them in one line what you
saved:
- **`USER.md`, under "In short":** their name first, then what they do; a second line with the
  tools they use.
- **`FLEET.md`:** one row per tool and account, with where it's used and what for. Level and
  Checked stay blank until it's connected.
- **`LEARN.md`:** above the Starting point table (leave the table as it is), one line:
  `Self-rated overall: N [stated YYYY-MM-DD]`. In the line starting `curriculum:`, replace the
  look-back placeholder with the date one month from today, as `YYYY-MM-DD`.
- **`START.md`:** if you can run code, copy the public template into your workspace, apply the
  same changes there, run `python3 scripts/tidy.py .`, and save the `START.md` it makes.
  Otherwise change three things by hand: the title ("<Name>'s rucksack (generated <today>)"),
  "Me in six lines", and "Still setting up" (the items still unticked, after the tick below). A
  nightly job in their GitHub keeps it current from tonight.

Tick "Saved in your GitHub account" in `ONBOARDING.md`, before you save `START.md`.

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

Then ask them to start a new chat and send "What does the first line of my rucksack's START.md
say?", and tell you the answer. (Asking what it knows about them isn't a test: this app may
remember today's chat.) When it quotes the title you wrote, this tool reads the rucksack by
itself and can write to it: record it in `FLEET.md` (Level: wired, today's date) and add it,
ticked, under "AI tools connected to your rucksack" in `ONBOARDING.md`.

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

Under "AI tools connected to your rucksack" in `ONBOARDING.md`, below the comment, add one line
per tool: `[x]` if connected, `[ ]` with a short note if it's for later ("Claude Code on the
laptop: next time at that computer"), `[-]` if they'd rather not. Every AI that reads their
rucksack mentions the next `[ ]` once a chat, and may tick it when it's done. Tick the main item
when nothing under it is left as `[ ]`.

## Finish

Show the setup list. Then:
- **What works now:** name the tools that know them and can update their rucksack.
- **What's next:** "Learn about your rucksack" (a short tour of their own files), then
  "Customise your rucksack", then "Set up your learning profile". Offer to start now, or any time
  with "let's carry on setting up my rucksack". (In this test copy those three aren't built yet;
  if they ask, say they're coming.)
- **Where it lives:** github.com/<username>/rucksack.

Save `ONBOARDING.md`, then leave a note in `memory/` as `AGENTS.md` describes. From here on,
`AGENTS.md` in their repository governs every AI working in their rucksack.
