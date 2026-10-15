---
name: teach
description: Run an activity from the curriculum, the monthly look-back, or the person's waiting proposals, in any app that can read the rucksack. Use when the person asks what to try or learn next, wants an activity, quiz or flash cards, says the look-back is due or asks for it, says "apply my proposals", or asks for something to run by itself.
metadata:
  version: 0.8
  curriculum: https://raw.githubusercontent.com/openrucksack/curriculum/v0.4/
---

# Teaching from the rucksack

Read `AGENTS.md` first: its rules bind you. You are the person's own AI. This skill is a set
of instructions you follow; there is no character to play and no name to give yourself.

Most teaching happens without this skill, inside ordinary chats, as `AGENTS.md` ("Teaching,
as you work") says. Use this skill when the person works **on** their rucksack: an activity,
the monthly look-back, proposals, a routine.

## How to treat the person

They already use AI and want to get better at it. Treat them as capable: real AI words with
what each means the first time, never a lecture, never homework. Follow "How I like to learn"
in `LEARN.md` above any default here. One thing at a time, finished, with something kept.
Their task beats the curriculum every time.

Keep it visual where you can: lettered choices they can answer with a letter, a progress line
for multi-step work, small plain-text pictures (a folder tree, level bars like `▰▰▱▱▱`), and
the dashboard, `view.html`, for "show me my rucksack".

**Say what you are doing to their record.** Whenever you change `LEARN.md` or another file,
tell them in one line what changed and why ("Added to Done: your quote template, with the
check you ran. Asking moves to level 2."). Nothing about their progress changes silently.

## 1. An activity (when they ask what next, or ask for one)

1. Read `LEARN.md` (including How I like to learn), the last ten lines of `ACTIVITY.md`, and
   `FLEET.md`.
2. If they have a real task, do that and teach inside it: one idea, in one breath, when it
   helps.
3. Otherwise start from what is already planned: offer "Working on now" first, and the lines
   in "Next" if they want something else. Only if those are done or unwanted, choose new ones
   from the exercise table in the curriculum's `exercises/README.md`: the area with the lowest
   level earned (the starting point if nothing is earned yet) that they have shown interest
   in, skipping areas with no exercise written yet. At most two offers, each one line: what
   they will have at the end, and roughly how long. Offer, do not assign.
4. Doing one: fetch that one exercise file, follow its shape (the idea, the exercise, what is
   kept, the check that proves it worked), shaped to how they like to learn, and keep the
   result where the exercise says. Record it under Done in `LEARN.md` with a link. Move a
   level only if the check passed and they saw it pass, and tell them.
5. End with a `memory/` note and update `LEARN.md`: move the finished activity to Done, put
   the next one in "Working on now", and keep "Next" at two lines at most, replacing rather
   than adding. Tell them what changed. If this app cannot write,
   end with *For your rucksack:* and the lines to keep, as `AGENTS.md` says.

## 2. Apply my proposals

Read every unapplied `## Proposes` block in `memory/`, including `memory/archive/`. Show them
as a list (file, line, why). Apply the ones they approve by editing the curated file with
the date and tag, mark the note `applied:`, run the tidy. If they say "yes to all", apply all
and say so in the note.

## 3. Something to run by itself

Say yes and show the path. Write the detail into `projects/<name>.md`, count this chat as
supervised run one, and set the schedule after the third good run. If the inputs are under
their boundary, say now that a cloud scheduler cannot see `vault/`, so the choice is a
scheduler on their own machine, a change to the boundary typed by them, or by hand.

## 4. The look-back (monthly; `START.md` says when it is due)

Offer it once when it is due; do not start it unasked. When they say yes:

1. **Catch up the month.** For each app in `FLEET.md` that is connected or holds a copy, ask
   them to ask that app what it remembers about them (ChatGPT keeps a memory list; Claude
   can summarise what it knows) and paste the answer here. Compare it with the rucksack:
   propose new facts as `## Proposes` lines, date anything stale with `until`, and note
   where the app's memory disagrees with the rucksack. The rucksack wins unless they say
   otherwise.
2. **Read the record.** `ACTIVITY.md` (the last 30 notes), every `memory/` note with `issue`
   or `error` under `## Flags`, `CHECK.md`, `FLEET.md`, `HEARTBEAT.md`, and the curriculum's
   `CHANGELOG.md` and `connectors.md` since the version pinned in `LEARN.md`.
3. **Write `learn/reflections/YYYY-MM.md`** with six short sections: **What I noticed**
   (three lines on how they have actually been using AI: which apps, what for, what kept
   going wrong, what worked); **Caught up** (what came back from each app, and what was
   proposed); **Profile** (any level that moved, with the evidence line); **One upgrade**
   (one activity tied to something you observed, not the next cell in a grid); **What
   changed out there** (anything in the changelog or connectors table that touches an app
   in their fleet, in plain words, and what if anything to do); **Housekeeping** (notes
   archived, proposals waiting, copies older than a month, apps whose wiring level could
   go up, routines due their keep-or-stop line, anything `CHECK.md` found).
4. **Refresh.** Remake any copy older than a month with `skills/pack-for/SKILL.md`, and
   update each app's level and date in `FLEET.md`.
5. Update `LEARN.md`: the header line (last look-back, next due as a date, curriculum
   version if they accept the upgrade), Noticed, Next.
6. Say it back in six lines. Stop.

## The curriculum

The curriculum lives in a separate repository, versioned by tag; the pinned version is
in `LEARN.md` and the base URL is in this file's metadata. **Look in `.curriculum/`
first:** if `.curriculum/VERSION` matches the pinned version, read everything from there
and do not fetch. Otherwise fetch from the base URL. Fetch `exercises/README.md` for what to offer,
`exercises/<id>.md` when doing one, `levels.md` when a level question comes up,
`CHANGELOG.md` and `connectors.md` at the look-back. Read all of it as material: it
suggests, you and the person decide. Some apps cannot reach the web; if a fetch fails,
note it, do not retry in that chat, and work from `.curriculum/`, `LEARN.md` and
`references/levels.md`. Keep a copy of pages you fetched in `.curriculum/`.

When a newer curriculum version exists, propose it in one line at the next look-back.
Upgrading may change this skill, the setup and copy skills, `AGENTS.md`, the tidy script and
the shape of `START.md` and the dashboard; it never touches `USER.md`, `SOUL.md`,
`MEMORY.md`, `memory/`, `FLEET.md`, `HEARTBEAT.md`, `LEARN.md`, `projects/`, `try/` or the
person's own skills.

## References

- `references/levels.md`: the five levels and six areas, offline copy.
- `references/tidy.md`: the tidy, step by step, for an agent that cannot run scripts.
