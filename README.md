# ⏱️ Founder Time Audit

**Find out where your week really goes, and how many hours can come back to you.**

A free Claude skill by Ivan Bunin, co-founder of Pareto Talent. You give it your last two weeks of calendar. It gives you one page that shows what to **delete**, what to **automate** and what to **hand off**.

> 🔒 Your data stays in your own Claude account. We never see your calendar, your email or your results.

---

## 🧭 How it works (in plain words)

A "skill" is a set of instructions you add to Claude once. After that, you type `/time-audit` and Claude follows them. Nothing to code, nothing to run on your computer.

1. **💬 Two quick questions.** What your business does, and what you earn. That sets your **Buyback Rate**: the hourly value below which work should leave your plate.
2. **👀 A first read.** Claude looks at your last two weeks of calendar and tells you, in a few sentences, how many hours went to work someone else could do.
3. **🗣️ A few more questions.** Your goals, what gives you energy, when you do your best work.
4. **✅ A quick check.** Claude lists your meetings. You reply with the numbers that did not happen, or ran long or short.
5. **📄 Your page.** The hours that can come back, who should take them, a week view of what breaks your focus time, and a scorecard against ten time-management laws.

⏳ **Total time: about 20 to 30 minutes.** It works best while you still remember your last two weeks, so run it today.

---

## 🛠️ Install (once, about 3 minutes)

Do this on a computer, at [claude.ai](https://claude.ai). We recommend a paid Claude plan (Pro or higher): the audit is long, and on a free plan Claude can stop before your page is ready.

**Step 1 ⬇️ Download the skill**
[**Click here to download time-audit-skill.zip**](https://github.com/pareto-talent/founder-time-audit/raw/main/dist/time-audit-skill.zip). Do not unzip it.

**Step 2 ⬆️ Upload it to Claude**
Go to **Customize > Skills**, click **+**, choose **Upload a skill**, and pick the zip you just downloaded. Make sure the skill is turned on.

**Step 3 🧮 Turn on code**
Go to **Settings > Capabilities** and switch on **Code execution and file creation**. The audit needs it to do the maths.

**Step 4 📅 Connect your calendar**
Go to [claude.ai/settings/connectors](https://claude.ai/settings/connectors), click **Connect** next to Google Calendar, and sign in with the Google account your calendar is on.
Using Outlook or something else? Take a screenshot of each of your last two weeks in week view and attach them in the next step.

**Step 5 ▶️ Run it**
Start a new chat and type `/time-audit`. If that doesn't start it, just write "Run a time audit for me" and Claude will use the skill.

---

## 🔁 Run it again every Friday

Type `/time-audit` in a new chat. At the end of your first run, Claude offers to keep your profile (your goals, peak hours and ideal week) so you can skip the questions next time. Paste it into a Claude Project's instructions, or save it in a note.

## 🎯 Make it sharper

Your first page uses your calendar only. At the end, Claude offers to add your sent email and your call recordings (Fathom, Otter, Fireflies). That makes the numbers more exact.

## 🙋 Questions

**Do I have to install anything?**
No. There is a paste-in version that works in any Claude chat: [open the document](https://docs.google.com/document/d/1rKrZUebyOPjDbhsV40oxPMcP7PRyYWXE/edit?usp=sharing), copy everything, and paste it into a new chat.

**Is it safe to connect my calendar?**
You connect it to your own Claude account, and Claude reads it there. We are not in the middle and never see it.

**Claude says it can't find the skill.**
Check that it is turned on under Customize > Skills, and start a new chat before typing `/time-audit`.

**Where do I get the newest version?**
Download the zip again from Step 1 and upload it the same way. See [CHANGELOG.md](CHANGELOG.md) for what changed.

## 📦 What is inside

```
time-audit/
  SKILL.md                    the steps Claude follows
  references/methodology.md   the ten laws, their sources and the scorecard
  references/onboarding.md    the nine questions
dist/
  time-audit-skill.zip        the file you upload
```

You can read every line of it. Nothing is hidden.

---

## 👋 Built by

Ivan Bunin, for the founders in the Pareto Talent Delegation Mastermind.

Want a right hand to take the work in your Delegate column? [See how Pareto Talent matches founders with executive assistants](https://paretotalent.com/matching?utm_source=github&utm_medium=readme&utm_campaign=time-audit).
