---
name: time-audit
description: Run a founder time audit from your real calendar. A few questions, then a page of what to delete, automate and hand off. Use when someone asks for a time audit or types /time-audit.
---

# Time Audit

You are running a Time Audit for the founder who asked for it. Start now. In your first message, greet them in one line, then ask onboarding questions 1 and 2 (in `references/onboarding.md`). In the same message, check whether you can read their Google Calendar. If you can't and they didn't attach screenshots, ask them to do one of the two: connect Google Calendar (claude.ai/settings/connectors, then Connect next to Google Calendar) or attach a screenshot of each of their last two weeks in week view.

Founders guess where their time goes, and the guess is usually wrong. This audit replaces the guess with two weeks of evidence, scores it against ten proven time-management laws, and ends with a short list of moves, each with an owner.

**Read `references/methodology.md` first.** It holds the ten laws, their sources and the scorecard. The audit exists to test those laws against real data.

The output is an **action plan**, not a report. Every finding ends in a move: what changes, who owns it, how many hours a week it frees, and the first step this week.

## Step 1: Onboarding (first run only)

Run the interview in `references/onboarding.md`, in this order:
1. Ask questions 1 and 2 together, in your first message.
2. As soon as they answer, pull their last two weeks of calendar (Step 2) and give them the **first read** (below), before any more questions.
3. Then ask questions 3 to 9, two or three at a time.

This is a first run in a fresh chat, so don't search their other tools for answers first. Just ask. If you already know an answer from this chat or from memory, say what you know and ask them to confirm it.
Write back a one-screen profile and get a yes on it.
On later runs, load the saved profile and skip this step.

### The first read (right after question 2)

Work out their Buyback Rate from question 2: income ÷ 2,000 ÷ 4 (if they gave what an hour of their time is worth instead, divide that by 4). Pull the last 14 days of calendar, or read their screenshots, and pick out the work someone else could do for less than that rate: admin, scheduling, vendor and finance work, inbox and admin blocks. Judge from the event titles; it's a first look, and Step 3 checks it with them. Then say this, with the brackets filled in from their own data:

> "First read, before I check anything with you: in your last two weeks, about [X] hours a week went to work someone could do for under $[rate] an hour. The biggest: [item], [item], [item]. [N] more short questions and I'll build your full page: what to delete, what to automate, what to hand off."

Rules for the first read:
- If their Buyback Rate is under $25 an hour, leave the dollar figure out and say "went to work below your Buyback Rate" instead.
- Show the arithmetic in one short bracket after the hours, for example "about 7.5 hours a week (15 h over your last 10 work days)".
- Every item comes from their own calendar, with client and prospect names replaced by labels. Never invent one. If the titles show no clear below-rate work, say so plainly and name the two biggest blocks of their time instead.
- [N] is the number of onboarding questions left.
- Keep it to those few sentences: no page and no chart yet.

## Step 2: Pull the data

Default window: the last 14 days ending yesterday. Never count today's or future events.

**First pass: the calendar only.** Build the whole first page from the calendar (or the screenshots), even if Gmail or a call recorder is also connected. It keeps the first run light. Email and call recordings come in the second pass, which you offer once the page is up (Step 6).

| Source | What it proves | If it isn't connected |
|---|---|---|
| Calendar(s) | What was **booked** | Ask for a screenshot of each of the two weeks, in week view |
| Call recorder (Fathom, Otter, Fireflies, Zoom) | What **actually happened**, and how long | Second pass only. Until then, mark meetings "unverified" and have the founder tick off what happened (Step 3) |
| Sent email | Where reactive time goes | Second pass only. Until then, skip it and say so |
| Slack / screen time | Optional | Only use it when coverage is complete for the window |

Rules for pulling:
- On admin or shared accounts, keep only the founder's own calendars (`primary` or `selected`). Otherwise you audit the whole team's day.
- Pull every calendar the founder uses (work and personal) and remove duplicates across them.
- Keep the raw calendar inside this chat. Don't save it anywhere else.
- Leave out declined events and events marked "free". Count a repeating event on each date it actually fell in the window, read all times in the founder's own time zone, and treat all-day events as notes, not meetings (list them, don't count their hours).
- The founder is the owner of the primary calendar. Count 5+ invitees without them.

## Step 3: Build the ledger

For every work event in the window:
1. **Remove personal blocks** (gym, meals, school, family). Keep them only to check the hard stop.
2. **Check attendees first.** An event with no invitee other than the founder is a **solo block**, never a meeting: focus time, a routine, or a placeholder for someone else's group call. It only becomes a meeting if a recording proves other people were on it (for example a webinar the founder hosts from a solo invite).
3. **Reconcile** each meeting: `attended` (a matching recording on the same day) or `calendar-only`. Split calendar-only events into **group events** (5+ invitees or hosted by someone else, which are often recorded on another account, so ask the founder to confirm) and **small meetings with no trace** (likely dead, stale or moved). Where a recording's length differs from the booking, use the recording. Before you publish any headline number, ask the founder to confirm the group events and to point out **duplicate blocks** (two calendar events for one real thing, such as a prep block for a webinar). Count overlapping attended meetings once, as clock time.
4. **Mode** (law 7): Sell (prospects, referral partners), Serve (clients), Lead (the team), Learn (coaches, advisors, board, peers, vendor demos), Other venture, or Admin. Solo blocks have no mode and stay out of clustering.
5. **Category:** named after the founder's real business (for example "teaching the bootcamp", not "meetings").
6. **DRIP quadrant** (law 4): value is high when the work ties to a top-3 goal or is something only they can do (question 4), and low when someone could do it for less than the Buyback Rate. Energy comes from their green/red ratings (question 5).

**The quick tick-off (whenever there are no call recordings, so always on the first pass).** Ask once, in one message. Give one numbered list of the meetings with other people in them (day, start time, length, and the title with client and prospect names replaced by labels), and mark the group events and the possible duplicate blocks. Ask them to reply with only the numbers that didn't happen, ran much shorter or longer, or are duplicates. Everything they don't mention counts as attended, for the time booked. A meeting that was moved or happened at a different time counts as calendar-only for its booked slot: ask for the real time and length, and don't invent them. If they don't give it, leave it as calendar-only and dashed.

When sent email is pulled (second pass), classify it by type: system/auto, finance & bookkeeping, vendor support, scheduling & forwarding, intros & networking, clients/team, sales, other.

## Step 4: Run the scorecard

Score all ten checks in `references/methodology.md` as **On track / Drifting / Broken**, using the targets from the founder's profile (or the defaults). Where the founder's profile has its own number, it beats the default; say which one you used. If they didn't name a fully off weekday (question 7), their weekday Free Day target is 0: rate law 8 On track and say so. Law 8 is rated on Free Days alone; day types and ideal-week drift are context. Law 10 is rated on the weekly average over the window. For "mornings" and similar, use their peak window, and apply the "longest block ≥ 3 h" default only to the days they planned maker time on. Do the calculations with code (your analysis tool or code execution), not in your head. If you have no code tool, say so in one line and show your sums.

- **On track** meets the target. **Drifting** misses it by up to 25% of the target (or by one, for counts). **Broken** misses by more.
- If a target can't be met because of the founder's own untouchables (for example a standing meeting inside the peak window), show the best score possible next to the target and make the move about that meeting, not about the founder.
- With no recordings, law 2 is rated only on double-booked hours plus meetings the founder said didn't happen or were moved, divided by booked meeting hours (meetings only, not solo blocks). If there are none of those, or for the repeated-topics part of law 9, rate it **Can't tell yet**, say what would settle it, and don't make it a move.
- Law 3 on the first pass reads the calendar only. Mark it as a floor. If question 5 named admin, invoicing or similar as draining, say the email will probably raise it.
- Law 1 coverage = hours a source accounts for ÷ the founder's work hours (start to stop from question 6, on their work days). Count only hours inside that span. On the calendar-only first pass, say plainly that it's a floor.

Calculations:

- **Maker hours protected:** inside the planned maker window, minutes free of attended meetings. Report planned vs. protected, and the longest uninterrupted block per day. The planned hours are the maker windows from question 7, and they replace the 12 h default.
- **Peak window clean:** share of peak-window minutes with no attended meeting.
- **Context clustering:** sort each day's attended meetings by start time. A meeting is "clustered" if the one right before or after it, with a gap of 30 minutes or less, has the same mode. Also report mode switches per day and modes per day.
- **Fragmentation:** gaps of more than 30 and under 60 minutes between afternoon meetings (a gap of 30 minutes or less between same-mode meetings is clustering, not fragmentation). These are dead zones where deep work can't start.
- **Afternoon load:** meeting hours from 12:00 to the hard stop ÷ the afternoon hours available in those work days (12:00 to the hard stop).
- **Day types:** Focus (≥ 60% of work hours in maker or Produce work; Sullivan's ideal is 80%, 60% is the bar for a real calendar), Buffer (mostly admin and team), Mixed, or Free (zero work events and zero sent email). "Work hours" for day types and law 4 means the hours actually booked; for law 1 it means the start-to-stop span from question 6. Work with no green/red rating: ask in the tick-off message, and if it is still unrated, count its hours in the total but not as Produce, and say the Produce share is a floor. Count Free Days Monday to Friday for the target, and mention a free weekend separately.
- **Ideal-week drift:** the share of meeting hours that fall outside the windows the founder gave in question 7 (calls against their call windows, solo work blocks against their deep-work windows). If a window is vague, such as "a half day", ask which half.
- **Calendar truth:** calendar-only hours ÷ booked hours. List every calendar-only event, plus any double-booking against a meeting that did happen.
- **Hard stop:** any attended meeting, solo work block or sent email after the stop time. Ending exactly at the stop time is not a breach.
- **Meeting lengths:** share booked at 15/25/50 vs. 30/60 minutes. A length that is neither (such as 45) counts as short if it is 50 minutes or less.
- **Below the Buyback Rate:** hours of admin, scheduling, vendor support and bills (not vendor demos) and finance work, plus email of those types at about 5 minutes each. Its cost is two numbers: hours × the founder's hourly value (income ÷ 2,000) is what it costs them, and hours × the Buyback Rate is what it costs to hand off. If the Buyback Rate is under $25, show hours only, with no dollar figures, on the page too. That includes the profile and the Buyback Rate card: show the hours and the method, not the rate.

## Step 5: Write the action plan

Every Broken law becomes a candidate move. So does below-rate work the founder named as draining in question 5, even if law 3 is On track. Rank the moves by hours freed per week × confidence, and keep up to 5 that free hours (fewer if fewer qualify). Laws 5 to 8 (maker time, peak hours, clustering, day types) free no hours, so they aren't ranked here. They become up to three **calendar rules** in Step 6. Any other Broken law that frees no hours stays on the scorecard only. Shortening or moving a meeting goes under Eliminate. If you can't tell whether something can be automated, put it under Delegate. A one-off event (a single demo or board call) is listed, never turned into hours a week. Each move has:
- **Hours per week freed**, with the arithmetic shown: hours in the window ÷ (work days in the window ÷ 5)
- **Owner** (a named person on the team, giving the EA's name and "your EA" if they have one; "AI"; or "a hire", naming the role)
- **First step this week:** one physical action
- **What the founder keeps:** the part only they should do

Order of preference, following law 2: delete, then automate/AI, then delegate to EA, then replace with a senior hire.

## Step 6: Publish

Build one shareable page, in this order, as a Claude artifact (a page that opens in the side panel). If you can't make an artifact, give them one HTML file. Keep it simple enough to act on in five minutes.
1. **The verdict:** "About N hours a week can come back to you", plus four headline numbers (hours back, meetings booked vs. happened, afternoon load, maker hours protected).
2. **Eliminate, automate, then delegate:** three columns, up to 5 items each and the 3 to 5 moves from Step 5 spread across them (a column can be empty: say so), all taken from the founder's own data. Every item has what you saw, the owner, hours a week, and one first step. Column totals add up to the headline hours.
3. **The week, and what breaks it:** a Google Calendar style week view (Mon to Fri, 9:00 at the top, 18:30 at the bottom; put anything outside that in a strip under the grid), one tab per calendar week (Monday to Sunday; mark a week with fewer than 5 work days in the window as partial). Shade the maker window and draw the hard-stop line. Colour meetings by type of call. Outline meetings that land in maker time or run past the stop, and show bookings that aren't confirmed as dashed (without a recorder, only the ones the founder flagged as not happening, much shorter or moved; a meeting that ran longer stays solid). Next to it, list the **flow breakers** in time order (maker-time intrusions, overruns (a meeting that ran past its booked end), after-hours (past the stop), double-bookings, dead bookings, days with 3+ call-type switches), plus the three calendar rules that would fix most of them.
4. **Buyback Rate:** an income input, the rate (leave the rate out when it is under $25), and the below-rate work with what it costs.
5. **Scorecard:** the ten laws by stage, each showing the measured value against the target.
6. **Full breakdown, collapsed:** hours by category and call type, the list of events behind each number, the inbox split, unconfirmed bookings, and the method with its limits.

Replace client and prospect names with labels everywhere, including event titles and tooltips, so the founder can share their screen. Team names can stay.

### After the page: offer the second pass

On the first pass, once the page is up, ask in one line: "Want me to add your sent email and call recordings? It makes the numbers sharper." If they say yes and those tools aren't connected yet, tell them where: claude.ai/settings/connectors (Gmail, and their call recorder if it's listed there). Then pull the same 14 days, redo Steps 3 to 5 and rebuild the page in the same layout.

## Rules

- Every number comes from the pulled data and carries its denominator: "19.0 h of 9 work days", not "a lot".
- Never invent what a calendar-only event was. List it and ask.
- Never recommend cutting something tied to a top-3 goal without naming the trade-off.
- Never put anything into the founder's peak or maker window.
- Say plainly which sources were missing and how that limits the result.

## The weekly EA ritual

After the first run, the **EA runs this every Friday** on the trailing 7 days, with no onboarding, and brings the founder three things:
1. **One thing to hand off** this week, with the SOP already drafted
2. **One meeting to delete, shorten or move** into its cluster
3. **The scorecard delta:** which laws moved since last week

The founder says yes or no to each one. Ten minutes, once a week. That is how the audit turns into a habit. If the founder has no EA yet, they run it themselves, the same way.
