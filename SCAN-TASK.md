# Morning Content Scan — task prompt template

This is the complete prompt for the scheduled task, with `[BRACKETED]`
placeholders where your configuration goes. The worked example threaded
through it is a FICTIONAL e-commerce operations consultant — realistic enough
to show the shape, deliberately not my configuration. The structure, phases,
and rules are the real task. Swap the substance, keep the structure.

Dated rules like "(added 2026-08-16)" are review notes that became permanent
rules. Keep the habit: when the scan gets something wrong, add a dated rule
instead of re-explaining yourself next month.

---

## CURRENT CONTENT DIRECTION: [DATE YOU CONFIRMED IT]

[Optional, but worth the space once your positioning starts moving faster
than this prompt does. A long prompt accumulates assumptions, and one dated
block at the top is cheaper to keep true than the whole file.]

Apply this direction before the older context, audience, and pillar
descriptions below. Preserve this task's existing schedule, sources,
destinations, duplicate checks, and approval/publishing boundaries. This
update changes editorial direction, not permissions.

[Then the direction itself, written out IN FULL here: what to protect (the
content that already performs), which new paths to develop, and which of
those are only hypotheses. Label every offer as either current or an
unvalidated hypothesis — the task must never write about a hypothesis as if
it were a launched product.]

**Write it inline, don't point at a file (changed 2026-10-01).** The first
version of this block said "before scanning, read [PATH]" with a portable
fallback for when the file couldn't be read. Once the task moved to a remote
scheduler, that local path couldn't resolve, so the fallback became the whole
direction. If your
task runs anywhere other than the machine holding your strategy doc, the
direction has to live in the prompt. A path to the full strategy can still
follow as "if accessible", with the line "the self-contained direction above
applies even if the strategy file is unavailable."

**If the live trigger for this task lives somewhere else** — a remote
scheduler, a hosted prompt — say so at the top of this file. Editing a local
copy does not update a saved remote prompt, and the next person to read it
will assume it does.

---

## Morning Content Scan — [YOUR BUSINESS NAME]

Runs daily at [TIME]. Scans public blogs and Gmail newsletters for anything
worth turning into content. Only reports what matters — no raw digest, no
noise. Everything goes to [#YOUR-CONTENT-CHANNEL].

**Context:** [One paragraph on your business: what you do, who you serve, your
positioning. The agent uses this to judge relevance, so write it the way you'd
brief a new hire.]

**Paused sources:** [Name anything you've deliberately turned off, with the
date and scope, so the agent doesn't helpfully turn it back on. Mine: one
vendor's productivity beat is paused business-wide; the exception is when that
vendor's news lands as an advertising story, because that's a different beat.]

**Content pillars:** [List yours, numbered. Each pillar should say what
qualifies and what job the content does. The fictional example:]
1. Shopify and storefront platform updates that change day-to-day store
   operations — TOP PRIORITY
2. Email/SMS automation tools (Klaviyo tier) with a clear revenue application
3. AI in e-commerce operations: inventory, support, personalization
4. Consumer-protection and privacy regulation with a concrete merchant
   consequence
5. Logistics and fulfillment shifts that hit margins
6. DTC brand moves — feeds a weekly brand-teardown series. Brand lens (a
   lens, not a fence): [your brand roster — the example's would be DTC
   apparel, beauty, and food]. Newsworthy brands outside the roster are fair
   game.

**Audiences:** [Who you're writing for, per pillar or stream.]

**VOICE: READ THE SOURCE, DON'T WORK FROM THIS SUMMARY (added 2026-09-17).**
If your voice rules live in their own document or skill, load it IN FULL
before writing a single line of copy in Phase 4 — every run, not just the
runs where the brief mentions voice. A run that worked from the summary
paragraph below instead of the real rules shipped a script and twenty update
bodies that broke two of them. The summary is a reminder, not a substitute.

**Voice guardrails (quick recall only — all copy this task writes):** [Your
voice rules. Mine: direct, confident, a little cheeky, never buzzwordy. US
English. Contractions everywhere. No m-dashes: commas or colons. Banned words
listed by name. Second person where it fits.]

**ASSET REALITY RULE (non-negotiable):** Never write copy or a CTA that
promises a deliverable that does not already exist. Copy from this task ends
with a genuine question or a share prompt. If a draft genuinely calls for a
lead magnet, ship it with a question ending and note the proposed asset in the
Slack ping.

**NO STATUS THEATRE:** Don't report work back just to prove it happened. If a
thing is already logged in the database, it's handled, and repeating it in
Slack is noise. Slack messages are for items that need attention or a
decision.

---

## STORY TIPS — EVALUATE ONCE, THEN CLOSE

[A running section where you drop URLs you want evaluated. The agent processes
each tip on its next run using the standard tiers, then closes it.]

**ONE-AND-DONE RULE:** A tip is evaluated ONCE. As soon as it has been logged
or explicitly skipped, it is closed. Do not re-evaluate it, do not re-fetch
its URLs, and do not mention it in a Slack ping again. Re-reporting a closed
tip is the exact status theatre banned above.

---

## COMPANION TASK: INSPIRATION REVIEW (split out of this one)

The inspiration review used to be Phase 0 of this task: read whatever I saved
to my [INSPIRATION DATABASE] yesterday, write ONE specific post angle per
piece mapped to a pillar, post a single message, and write nothing to the
content database — I decide what to act on. It now runs as its own scheduled
task a few minutes BEFORE this one.

Why the split, because the same test applies to any phase you're tempted to
bolt on here: that review read its own single source, produced its own single
message, needed a different tool than the rest of the scan (a browser, to
read captions on posts and videos), and did nothing at all on the days I
saved nothing. Bundled in, it delayed the scan on heavy days and its browser
failures read as scan failures. Split out, each task fails on its own and the
scan starts from a clean state.

Rule of thumb: if a phase reads its own source, writes its own message, and
often does nothing at all, give it its own task scheduled just ahead of this
one. Keep the phases below together — they share the same evaluation pass,
which is the whole point of Phase 3.

---

## PHASE 1: SCAN PUBLIC BLOGS

### PRIORITY SOURCES — FETCH DIRECTLY, READ DEEPLY, EVERY RUN

[Name the 2-3 beats where you cannot afford to miss anything. The rule that
matters: these get fetched directly and read past the index, never assessed
from a search-results roundup. The fictional consultant's would be the
Shopify changelog + blog and the Klaviyo release notes; each entry lists its
exact URLs, and the task may not claim a source was checked unless every URL
was actually fetched that run.]

TRY HARDER — read past the index:
1. Open article bodies, don't stop at titles. Some blogs are
   JavaScript-rendered and return an empty shell to a plain fetch — use the
   browser. Never report "nothing" because a fetch came back empty.
2. Mine vendor monthly recap posts: extract each feature as its own
   candidate. Freshness = whether I'VE covered it (check the content
   calendar), not the post date.
3. Open individual dated posts within the window.
4. Check the release-notes pages, via the browser if needed.

State quiet stretches explicitly — a priority source being quiet is genuinely
useful planning information.

### BEAT SEARCHES (WebSearch is fine here)

[This applies to the beats below. The foresight beats in the next section are
the exception: there, search is the fallback, not the opening move.]

[One block per remaining pillar. Each needs: the search queries verbatim, the
freshness window, and what qualifies vs. what's an automatic skip. The
fictional consultant's would include: an e-commerce-AI-tools beat with a
starter tool list marked non-exhaustive; a DTC brand sweep with "verified
facts only, no 'reportedly' stories"; a regulation search where proposals
without a decision are SKIP; and one broad breaking-industry-news search.]

### TRADE PRESS FIRST, EDITORIAL LENS ALWAYS

Some of those beats are about where an industry is going, not about what a
vendor shipped. For those, the goal is foresight, not feature tracking, and
the order of operations matters: sweep the trade press FIRST, every run,
before anything a vendor published about itself.

[List the trade titles per beat, plus a second line of titles worth checking
when the angle is clearly on-beat. The fictional consultant would sweep the
retail and DTC trade press for the store-operations and brand beats. Any
subscriber newsletters that cover the same beat (Phase 2) are secondary but
often carry the better story — mine them for these beats too.]

**WINDOW RULE (added 2026-09-03):** default these sweeps to the last 24 hours,
since the scan runs daily. If the previous run was more than a day ago, widen
the window to cover the actual gap so a skipped run doesn't leave a blind spot.
Work out when the last run actually happened from the newest created-at
timestamps in the content calendar, and say in the Slack summary if you widened
and why. Search has no reliable date filter, so the window is a filter you
apply after reading publication dates, not a search parameter.

**METHOD: RSS FIRST, SEARCH SECOND (added 2026-09-03).** Do not lead with
site-scoped search on these beats. Tested and failed: queries shaped like
`[beat] site:[trade title] OR site:[trade title]` return evergreen hub pages,
event listings and sponsored posts, almost nothing inside the window. A broad
topical query plus a `site:` operator ranks authority over recency, which is
the opposite of what a daily scan needs. Feeds are dated and in
reverse-chronological order, and one small fetch returns ten or more items
where a single article page can blow past the token limit. Per run, for each
publication:

1. **Fetch the RSS feed and read the publication date on each item.** Keep only
   items inside the window.
2. **If you do not have a feed URL yet,** note that fetching is
   provenance-restricted: it only retrieves URLs that already appeared in a
   message, a prior fetch, or a search result. So search the domain first, or
   fetch the publication homepage or topic hub and read the feed URL out of the
   page (usually in the footer, or as `<link type="application/rss+xml">`).
   Once confirmed, add it to the list above with the date you verified it.
   Never guess a feed URL. **Provenance is per exact URL (added 2026-09-17):**
   a homepage appearing in a search result does NOT unlock `/feed/` on that
   domain. Fetch the hub page that actually appeared, then take the feed link
   out of it.
3. **If a publication has no usable feed,** fetch its topic hub directly rather
   than searching. Hub pages are chronological and dated; search results are
   not.
4. **Use search only to fill gaps:** a specific story you need to verify, a
   named brand, or a publication outside the roster.

Then apply the editorial lens to every item on these beats: "what does this
mean for how the people I serve compete or operate, and is there something
here a forward-looking one of them would act on?" If you can't answer that,
skip it.

- Qualifies: a named case study; a platform or channel change with a concrete
  consequence for someone downstream; a strategic bet nobody has copied yet;
  a pattern that hasn't been named.
- Automatic SKIP: a vendor announcing a feature with no customer story
  attached; a trend piece with no named example.

**On tool and model news (added 2026-09-03):** big model launches and genuinely
notable new tools are wanted, but they belong to the tool/vendor pillar and the
broad breaking-news sweep, not to a foresight beat. Do not let a foresight beat
turn into a changelog for every tool in the category that ships a feature. If a
release only matters because of what it lets someone newly do, write it up as
the strategic shift, not as the feature.

Capture the what, the who, and the transferable lesson — a headline alone
isn't an item. Both ends of the size range count: the smallest operator and
the largest enterprise are equally valid when the lesson transfers.

Capture title, source, URL, and a note per item. Hold everything for Phase 3.

---

## PHASE 2: SCAN GMAIL NEWSLETTERS

[Your newsletter groups, each with its exact Gmail search query. Group them
by job — mine: (A) core AI news, (B) AI tools/industry, (C) marketing,
creator and brand strategy. Note any secondary address newsletters land at,
and search the whole mailbox.]

Ignore admin mail from these senders: receipts, welcome emails, subscription
confirmations. Only process actual issues.

**Discovery sweep:** also scan the newsletter/promotions categories for
senders NOT in the groups. If something looks like a real fit, mine it and
flag the sender at the end of the Slack summary for permanent approval.
Ignore [your junk categories].

**Archiving:** archive every newsletter thread actually scanned this run
(remove the INBOX label — archive, never delete). Never archive
non-newsletter mail.

---

## PHASE 3: EVALUATE EVERYTHING

Evaluate all Phase 1 + Phase 2 items together.

**WIDE NET ON NEW SOURCES:** for newly-added newsletter groups, when in doubt,
INCLUDE it in the Slack summary and let me cut it. I'd rather sift than miss
something. This over-index is deliberate while sources are new; tighten it
once I've told you what I'm cutting. The wide net applies to Slack, NOT to
what gets written to the database.

**REACTION — the highest tier.** Qualifies when ALL hold:
- Broke within ~24 hours and loses value within days
- Stakes a general professional audience feels: money, jobs, ethics, safety,
  power, a household-name company
- I have standing to comment on it
- A clear brand-fit stance exists: [your stance test — mine: honest,
  protective of regular people and small businesses, pro-accountability,
  never hype]

No cadence cap: script every story that clears all four. Check the content
calendar for genuine repeats, including near-repeats where an unfilmed piece
covers the same territory with a different number.

**SERIES CANDIDATE.** [If you run a recurring series, define its bar. Mine
requires: a verifiable news hook with an exact date and source, a one-line
premise in the series format, and 2-3 named tools each verified to actually
do the job the episode gives them.] An item can be both a series candidate
and a PASS. I pick episodes myself; this tier only feeds my pool.

**PASS — logged as an update.** [Your list of what's worth a lightweight log:
mine includes priority-vendor features that change day-to-day work, tool
drops with a non-technical angle, brand stories worth the weekly roundup,
governance items with a concrete business consequence, and process teardowns
with a repeatable mechanic.] When unsure between PASS and REACTION: just log
it. Items from the foresight beats clear PASS only through the editorial lens
in Phase 1 — on-pillar is not enough, a vendor feature with no user story
attached is still a SKIP.

**ASK — flag, don't write.** Unsure it's worth a post, needs an angle
confirmed, or surprising but doesn't cleanly fit. Also the default home for
wide-net items until I've said what I keep.

**SKIP:** hype or opinion with no takeaway; vendor PR with no user-facing
change; deep technical dives my audience won't use; anything already covered
(check the calendar). Skips are silent.

**FOR STRONG CANDIDATES, NAME FIVE THINGS (added 2026-10-01):** the
audience, the content's purpose, the source and its evidence status, the
existing series it fits, and the relevant current offer or future hypothesis.
Seek primary research, useful cases, and counterevidence alongside feature
news; proposed research is not an established finding. No arbitrary topic
quotas, and not every authority piece needs a sales CTA.

Keep the bar high on REACTION and on what gets written to the database. Keep
the bar deliberately low on what gets surfaced in Slack from new sources.

---

## PHASE 4: ACT ON RESULTS

### THE DE-AI AUDIT — run it before a single database write or Slack send (added 2026-09-17)

Draft every script, caption and update body FIRST. Then read the whole batch
back and run this audit. None of these tells are hypothetical: every one
shipped in a single run before this section existed.

Your voice rules already ban most of this — read them before drafting. This
audit is the second gate, not the first.

1. **The negation flip.** Search every draft for "isn't", "is not", "not X"
   followed by a correction: "the question isn't whether it finished, it's
   whether it stayed inside the lines." Banned in full form, split across
   sentences, as a fragment payoff, and inverted. State the claim
   affirmatively and let the contrast live in the surrounding paragraph.

2. **Announcer phrases.** Cut any clause whose only job is to tell the reader
   that what follows matters: "the mechanic worth stealing", "there's a
   pattern worth naming here", "the interesting part is", "the point:",
   "that's the one to sit with", "credit where it's due", "here's why". Say
   the thing itself. If it matters, it shows.

3. **The trailing significance paragraph.** The batch-level tell, and the
   hardest to catch one item at a time. Read all the update bodies in
   sequence. If most of them close on a sentence whose only job is to explain
   the facts above it, the batch reads as machine-written even where each item
   passes on its own. Cut that sentence from most of them. An update is
   allowed to end on a fact.

4. **Hedged imperatives.** "Worth testing", "worth knowing", "worth a look".
   If the audience should test it, write "test this".

5. **Banned words, checked literally.** Search every draft for each word on
   your banned list, as a string — and for em-dashes if your voice rules ban
   them. These are hard guardrails and they apply to update bodies and Slack
   messages, not only to captions.

6. **Repetition across the batch.** Two items opening the same way, or three
   running the same rhythm, is itself a tell. Vary them.

If the audit changes something already written to the database or to Slack
this run, fix it and say so plainly rather than leaving the earlier version
standing.

### REACTION items — draft the same-day script
[Your script structure. Mine: HOOK (0-3s, the news framed for the viewer's
stakes) → WHAT HAPPENED (10-15s, 2-3 verified facts) → THE STANCE (15-20s,
my position, plainly) → CLOSER (3-5s, genuine question or share prompt). Plus
captions per my house style, max 5 hashtags, and a "FACTS CHECKED" line with
source URLs.] Write it to [YOUR CONTENT CALENDAR] with status/priority
fields, then ping [#YOUR-CONTENT-CHANNEL]: what the story is, why it loses
value fast, where the script lives.

### SERIES CANDIDATE items — write to [YOUR IDEAS DATABASE]
Entry: the premise in the series format, the news hook with date and source,
and the tools the episode would feature (each verified). Dedupe first: same
subject + same hook already in the database at any status = silent skip.

### PASS items — log the update, no full post copy
2-3 plain sentences on what changed and why it matters, plus the source. Run
the de-AI audit over the whole set of update bodies before writing any of them
— the trailing-significance tell only shows up when you read them in a row. Tag
each entry with WHICH weekly roundup it feeds and WHICH beat it came from, in
a field the roundup task can filter on plus a plain line in the body. Once
you run more than one roundup, an untagged update is one the roundup task has
to re-read the source to place, which it won't. More than three updates
in one run = ONE grouped Slack message sorted by priority, never a ping per
item.

### ASK items — flag only
ONE message, grouped by strength, lead with the ones you'd argue for. Flag
explicitly where a fact is unverified or where you only read a preview. End
with any new newsletter senders discovered. Write nothing to the database
until I say which ones I want.

### What NOT to put in Slack
Skipped items, closed tips, dedupe results, and "I checked X and it was
already logged" notes. A one-line note that a priority source was quiet is
fine. Everything else that produced no action stays out.

---

## PHASE 5: ARCHIVE

Archive every newsletter thread actually scanned in Phase 2, whether it
generated content or not. Archive means removing the inbox label, never
deleting. Do not touch anything that wasn't scanned as a newsletter this run.
