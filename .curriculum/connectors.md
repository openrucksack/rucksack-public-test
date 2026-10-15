# Which app can do what with a rucksack (checked 14 October 2026; refreshed monthly)

Changes this month: the Codex app is now the ChatGPT desktop app, which opens a folder and
lets you choose ChatGPT (with a Chat or Work toggle) or Codex. Claude's folder work
(Cowork) is on Pro and Max plans; Free is chat only.

| App | Reads a rucksack in git | Writes back | Loads it at the start of every chat | Plan | Reads a folder in Drive |
|---|---|---|---|---|---|
| Claude (web, desktop, phone) | Yes: a Project connected to the repository, or an ordinary chat told the repo name (tested 14 Oct 2026, phone app); a local folder only through Cowork on the desktop app, Pro and Max | Yes: wrote a note straight to main from the phone app (tested 14 Oct 2026) | Yes, Project knowledge; a standing instruction in profile preferences is untested | Every plan | Yes, via the Google Drive connector (read) |
| Claude Code | Yes (full git) | Yes | Yes (CLAUDE.md) | Pro and up | n/a |
| Claude Code Routines | Yes, a fresh copy each run | Yes, on a `claude/` branch with a pull request | Scheduled | Pro and up | n/a |
| ChatGPT desktop app, Codex mode (Mac, Windows, Linux; was the Codex app) | Yes (open the folder) | Yes (files; git if set up) | Yes (AGENTS.md) | Every ChatGPT plan including Free, with lower limits (secondary sources; OpenAI's page does not list plans) | Yes, as a folder |
| ChatGPT desktop app, Work mode | Uses files in the folder you open; whether it reads AGENTS.md is not documented | Unclear | Not documented | Not documented | Yes, as a folder |
| ChatGPT (web, phone) | Yes, through its GitHub connector; with the repo named in custom instructions a new chat read it by itself (tested 14 Oct 2026, phone app) | Yes: wrote a note straight to main through the connector (tested 14 Oct 2026, phone app) | Yes, with the standing instruction in custom instructions | Not confirmed which plans; tested on the owner's account | Yes, Google Drive connector (read) |
| ChatGPT Dots | As ChatGPT | Through Codex | Always-on agent | Pro | As ChatGPT |
| Grok and Grok Bot | Yes, GitHub connector (private repos were failing in Sep 2026) | In principle, same connector | When it decides it is relevant | Paid | Yes, Drive connector |
| Meta Muse | GitHub connector exists since 29 Sep 2026; what it can do is unpublished | Unknown | Unknown | Free | Unknown |
| Gemini app | One-off import of a repo on a computer, no sync | No (Jules can, by pull request) | No | Free | Read via Drive, natively |
| Microsoft Copilot (consumer) | No | No | No | n/a | OneDrive and Google Drive connectors (read) |
| OpenClaw | Yes (the workspace is a git repo) | Yes | Yes (every boot) | Self-hosted | Yes, as a folder |

The honest line this month: Claude and ChatGPT both read and write a rucksack on GitHub,
on the computer and the phone; connect GitHub in the web version on a computer first (on
14 October 2026 neither phone app offered the choice of organisation or repository). Gemini
and Copilot are read-only through Drive; everything else gets a copy.
Source and detail: appendix E of the research set.
