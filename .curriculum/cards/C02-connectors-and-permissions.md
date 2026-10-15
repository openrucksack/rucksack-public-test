---
id: C02
title: Connectors and permissions
area: Keeping it running
can-do: Gave an AI app limited access to my files, and chose how it asks before saving
checked: 2026-10-15
---

# Connectors and permissions

![A connector lets an AI app reach your rucksack: sign in, then allow one repository; it can read and write only what you chose, and asks before saving unless you say always allow](C02-connectors-and-permissions.svg)

**The idea.** A **connector** lets one app reach another for you: here, ChatGPT or Claude
reaching your rucksack in GitHub. It takes two parts: you sign in, so the app knows it's you,
and you choose what it may see, here just the one repository. That choice is a
**permission**. It can **read** (see your files) and **write** (save changes). When it saves,
the app checks with you first: **Allow once** asks every time; **Always allow** trusts that app
for that action from now on. Always allow is fine for your own rucksack if you're comfortable:
every change is still kept in GitHub's history, so you can see and undo anything.

**In your setup.** You connected this app and allowed it to see only `rucksack`.

**Check it landed.** "If you connected another app tomorrow, could it see your rucksack?" (Not
until they allow it too.)

**What proves it.** The app read their rucksack, and saved to it.

**For the AI.** When the first approval box appears, explain it in one line and offer "Always
allow", if the app offers it, as their choice, with what it means. ChatGPT's GitHub access comes
from OpenAI's GitHub app, "ChatGPT Codex Connector"; on 15 October 2026 signing in through
ChatGPT alone gave no access until that app was installed on the repository. Offer more if they
want it: other connectors they might use (email, calendar, drive), and the habit of giving each
the least access that does the job. Diagram, to draw if you can: the app on the left, the
rucksack on the right, the connector between them in two parts (sign in; allow one repository);
under it read, write, "only these"; then "allow once" versus "always allow".
