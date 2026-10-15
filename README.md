# Founder Time Audit

A Claude skill by Ivan Bunin, co-founder of Pareto Talent, for founders. It reads your last two weeks of calendar and shows you how many hours a week can come back to you, and who should take them.

After a few questions and a quick check of your meetings, it builds one page for you:

- the hours that can come back, split into what to **delete**, what to **automate** and what to **hand off**
- your **Buyback Rate**, and the work you do that sits below it
- a week view of what breaks your focus time
- a scorecard against ten time-management laws

It takes about 20 to 30 minutes. Run it today, while you still remember your last two weeks.

Your data stays in your own Claude account. We never see your calendar, your email or your results.

## Install (once, about 3 minutes)

Do this on a computer, at [claude.ai](https://claude.ai). We recommend a paid Claude plan (Pro or higher): the audit is long, and on a free plan Claude can stop before your page is ready.

1. **Download the skill:** [time-audit-skill.zip](https://github.com/pareto-talent/founder-time-audit/raw/main/dist/time-audit-skill.zip). Do not unzip it.
2. **Upload it to Claude:** go to **Customize > Skills**, click **+**, choose **Upload a skill**, and select the zip you just downloaded. Turn the skill on.
3. **Turn on code:** go to **Settings > Capabilities** and switch on **Code execution and file creation**. The audit needs it to do the maths.
4. **Connect your calendar:** go to [claude.ai/settings/connectors](https://claude.ai/settings/connectors), click **Connect** next to Google Calendar and sign in with the Google account your calendar is on. Using Outlook or something else? Take a screenshot of each of your last two weeks in week view instead.
5. **Run it:** start a new chat and type `/time-audit`.

## Run it again every Friday

Type `/time-audit` in a new chat. At the end of your first run, Claude offers to keep your profile (your goals, peak hours and ideal week) so you can skip the questions next time. Paste it into a Claude Project's instructions, or save it in a note.

## Make it sharper

Your first page uses your calendar only. At the end, Claude offers to add your sent email and your call recordings (Fathom, Otter, Fireflies). That makes the numbers more exact.

## Prefer not to install anything?

There is a paste-in version that works in any Claude chat: [open the document](https://docs.google.com/document/d/1rKrZUebyOPjDbhsV40oxPMcP7PRyYWXE/edit?usp=sharing), copy everything, and paste it into a new chat.

## What is inside

```
time-audit/
  SKILL.md                    the steps Claude follows
  references/methodology.md   the ten laws, their sources and the scorecard
  references/onboarding.md    the nine questions
dist/
  time-audit-skill.zip        the file you upload
```

You can read every line of it. Nothing is hidden.

## Updating

When a new version comes out, download the zip again and upload it the same way. The latest version is always at the link in step 1. See [CHANGELOG.md](CHANGELOG.md).

## Built by

Ivan Bunin, for the founders in the Pareto Talent Delegation Mastermind.

Want a right hand to take the work in your Delegate column? [See how Pareto Talent matches founders with executive assistants](https://paretotalent.com/matching?utm_source=github&utm_medium=readme&utm_campaign=time-audit).
