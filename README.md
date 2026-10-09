# Morning Content Scan

An AI research assistant that reads the news for you before you wake up.

Every morning at 4:30, Claude checks the websites and newsletters you care
about, decides what's worth your time, and leaves you a short Slack message
with only the things that need you. Stories worth posting about today come
with a script already drafted. Everything else gets filed for later. It saves
me about two hours of reading a day.

This is the real setup I use, shared as a template you can copy. It's the
second in my [systems-as-receipts](https://github.com/mel-greene) series,
after [reel-edit-system](https://github.com/mel-greene/reel-edit-system).

One honest note: the rules and steps are exactly what I run. The example
business inside is made up (an online-store consultant), because my own
topic list is the one part I keep to myself. You'll swap in yours anyway.

---

## Before you start

You'll need:

- **A paid Claude plan that can run scheduled tasks.** That's what lets
  Claude do this on its own every morning, without you opening it.
- **These apps connected to Claude:** Gmail, Slack, and Notion. (In Claude's
  settings, these are listed under connectors. Connecting one is a sign-in
  and an "Allow" button.)
- **A Slack channel** for the morning message. A new one is best, so
  nothing else gets buried.
- **Two Notion databases:** one for content ideas, one for your content
  calendar. Empty is fine. If you already use something else for this,
  Claude can work with that instead; just say so in the setup interview.
- **About 30 minutes.**

You don't need to code anything.

## Setup

**1. Download the instructions file.**
Open [SCAN-TASK.md](SCAN-TASK.md) above, then click the download button
(the arrow icon at the top right of the file). This file is the full set of
instructions Claude follows every morning.

**2. Let Claude fill it in for you.**
Start a new chat with Claude, attach the file, and paste this:

> This is a template for a daily content research task. Interview me one
> question at a time to fill in everything in the "Your setup" section at the
> top: my business, my audience, the topics I cover, the websites and
> newsletters I read, my Slack channel and my Notion databases. Then give me
> the finished file, with the example business replaced by mine and every
> rule below the setup section left as it is.

Answer its questions. When it's done, it gives you your finished version.

**3. Make it a scheduled task.**
In Claude, create a new scheduled task, paste in your finished version, and
set it to run daily at a time before you wake up (mine is 4:30 AM).

When it asks what the task is allowed to do on its own, allow only these
four things: archive Gmail emails, create Notion pages, update Notion pages,
and send Slack messages. Everything else stays read-only, so it can look but
not touch.

**4. Do a test run.**
Use "Run now" once instead of waiting for tomorrow, so you can check it
works while you're watching.

## What tomorrow morning looks like

- **One Slack message** (or none on a quiet day). It lists only the things
  that need a decision from you.
- **New pages in your Notion databases** for anything it saved.
- **Newsletters it read are archived** out of your inbox. Archived, never
  deleted: they're still in Gmail if you want them.

If something looks off, tell Claude what bugged you and ask it to add a rule
to the file. That's how this gets better over time: one new rule per
annoyance, never starting over.

---

## How it works

Every run has five steps:

1. **Read the websites.** Your most important sources get opened and read
   properly, article by article, not just skimmed from a list of headlines.
   Then it checks the industry press for each of your topics.
2. **Read the newsletters.** It searches your Gmail for the newsletters you
   named, and reads each issue.
3. **Sort everything into piles:**
   - **Post today:** breaking news worth reacting to while it's fresh. It
     drafts a script.
   - **Save for a series:** a good fit for a recurring series you run. It
     goes into your ideas database.
   - **Log as an update:** useful, not urgent. It's written up in two or
     three sentences and filed.
   - **Ask me:** it isn't sure. You decide.
   - **Skip:** not worth your time. You never hear about these.
4. **Act on it.** Write the scripts, fill in the databases, and send one
   Slack message.
5. **Tidy up.** Archive the newsletters it read.

## The rules that make it good

Every one of these exists because the scan got something wrong once:

- **No busywork reports.** It never tells you about work just to prove it
  did it. If something is filed, it's handled. Slack is only for decisions.
- **Each story gets looked at once.** Once it's filed or skipped, it never
  comes back.
- **Actually open the source.** "Nothing new" only counts after it has
  really opened the website, not after a search came back empty.
- **No promises you can't keep.** It never writes copy that offers a
  freebie or resource you haven't made yet.
- **Real examples over announcements.** A company announcing a feature,
  with no customer actually using it, gets skipped.
- **Newest news first.** For industry press it reads the sites' dated news
  feeds instead of searching, because search tends to surface old pages.

## Words you'll see

- **Scheduled task:** something Claude does on its own at a set time, like
  an alarm that runs a job instead of ringing.
- **Connected app (connector):** an app you've given Claude permission to
  use, like Gmail or Slack.
- **Prompt:** the written instructions Claude follows. SCAN-TASK.md is one
  long prompt.
- **Template:** a ready-made version you copy and change to fit you.
- **Notion database:** a table in Notion where each row is a page. Your
  ideas list and content calendar are two of them.
- **News feed (RSS):** a list of a website's newest articles, with dates,
  that tools can read. Most news sites have one.

## License

[MIT](LICENSE): free to use, copy, and change. The rules are my real
system, the example business is made up, and your setup is yours.
