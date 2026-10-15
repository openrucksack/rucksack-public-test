---
id: C01
title: GitHub and privacy
area: Staying safe
can-do: Keeps my AI context in a private place I control, and knows who can see it
checked: 2026-10-15
---

# GitHub and privacy

![Your rucksack is a private repository in your GitHub account: you, anyone you invite and the AI tools you allow can see it; GitHub staff only in rare cases; every saved change is kept](C01-github-and-privacy.svg)

**The idea.** GitHub is a website for keeping files, owned by Microsoft and used by millions of
people and companies. Your files sit in a **repository**, GitHub's word for a folder. A
**private** repository is seen only by you, anyone you invite, and the apps you allow; nobody can
find it by searching, and GitHub's staff look only in narrow cases, like a support request you
make, security, or the law. When an AI app you allow reads it, what it reads goes to that app's
company, like anything you type there. Every saved change is kept, so you can go back to any
earlier version.

**In your setup.** Your rucksack will be a private repository called `rucksack` in your own
account.

**Check it landed.** "Who will be able to see your rucksack?" (Them, anyone they invite, and the
AI apps they allow.)

**What proves it.** Their repository exists and shows "Private" next to its name.

**For the AI.** Address the worry directly: putting personal things into something called
"GitHub" feels odd if they don't know it. Points to have ready, all from GitHub's own documents
(checked 15 October 2026):

- GitHub says it does not train AI on private repository content at rest. If they ever use
  GitHub's own Copilot on it, they can switch off "Allow GitHub to use my data for AI model
  training" in their settings.

- Two-step sign-in protects the account; GitHub requires it for some accounts, and everyone should
  turn it on and keep the recovery codes.

- Something saved by mistake stays in the history; removing it properly takes more than deleting
  the file, so help them do it right. A deleted repository can be restored for 90 days; a deleted
  account can't.

- "Download ZIP" takes today's files; GitHub's account export takes everything.

- Their rucksack's tidy checks every night that it is still private, and warns them if not.

Diagram, to draw only if asked: their GitHub account holding a `rucksack` box marked Private;
beside it who can see it (you, people you invite, AI apps you allow; everyone else no; GitHub
staff only in rare cases); under it a timeline of saved changes.
