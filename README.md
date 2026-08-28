# Morning Content Scan

The AI research agent that runs my content pipeline while I sleep.

Every day at 4:33 AM, a scheduled [Claude Cowork](https://claude.com) task scans
my priority sources, my Gmail newsletters, and my own saved inspiration, then
sorts everything it finds into five tiers. By the time I'm up: breaking stories
have same-day reaction scripts drafted, series candidates are logged to my
content database, and the only Slack messages waiting are ones that need an
actual decision from me. Roughly 2 hours of research a day, done before I wake
up.

This repo is the real task, published as a working template — second in my
[systems-as-receipts](https://github.com/mel-greene) series after
[reel-edit-system](https://github.com/mel-greene/reel-edit-system).

## How it works

**[SCAN-TASK.md](SCAN-TASK.md)** is the complete task prompt. Five phases:

0. **Inspiration review** — reads whatever I saved to my inspiration database
   yesterday and suggests a specific post angle for each piece
1. **Public blog scan** — priority sources fetched directly and read deeply
   (index pages lie; the task opens article bodies), plus beat searches for
   each content pillar
2. **Newsletter scan** — three groups of Gmail newsletters, mined then archived
3. **Evaluation** — every item sorted into a tier: REACTION REEL (script it
   today), SERIES CANDIDATE (log it to the ideas database), PASS (log as an
   update), ASK (flag for a decision), SKIP (silence)
4. **Action** — scripts drafted, databases updated, ONE grouped Slack message
5. **Cleanup** — scanned newsletters archived out of the inbox

## The rules that make it good

The scan got sharp through review notes that became permanent rules, and
they're all in the task:

- **No status theatre.** The agent never reports work just to prove it
  happened. If it's logged, it's handled. Slack is for decisions only.
- **One-and-done.** A story is evaluated once, then closed. No re-reporting.
- **Read past the index.** "Nothing new" is only allowed after actually
  opening the source, not after a search-result roundup came back thin.
- **Asset reality.** Drafted copy never promises a deliverable that doesn't
  exist yet.
- **Wide net where sources are new, high bar for what gets written down.**

## Setup

1. You need Claude Cowork with Gmail, Notion (or your database of choice),
   Slack, and browsing connected.
2. Copy SCAN-TASK.md and replace every `[BRACKETED]` placeholder: your
   database IDs, Slack channel, newsletter senders, pillars, and voice rules.
   My real configuration is left in place as the worked example — swap the
   substance, keep the structure.
3. Create a scheduled task in Cowork with your edited prompt. Mine runs daily
   at 4:33 AM with pre-approved permissions for exactly four actions: archive
   Gmail threads, create Notion pages, update Notion pages, send Slack
   messages. Everything else stays read-only.
4. Tune it by adding rules, never by rewriting from scratch. When the scan
   annoys you, that annoyance is a missing rule: name it, date it, add it.

## License

[MIT](LICENSE). The configuration shown is mine; the structure is yours.
