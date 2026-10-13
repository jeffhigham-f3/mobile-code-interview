# Mobile Code Interview

Welcome, and thanks for taking the time. This repo is just the rules. You'll build the
app from an **empty folder** in your own repo during the session.

The session is **2 hours, entirely AI-driven**. We'll build a small production-quality
Flutter app together. I play the PM and your tech lead; you're the engineer holding the
AI. You'll get a short product brief at the start and each story's details as we reach
it, so there's nothing to read ahead on.

---

## What I'm looking for

This is a hard interview, and the difficulty is deliberate engineering, not speed.

- **Plan before you build.** Take real time on the architecture: layers, what may
  depend on what, where business rules live, how you'll test. Write down the
  conventions your AI should follow.
- **Every feature goes through a plan gate.** Before building a story, walk me through
  a short plan. I'll approve it, or ask for one change, as a tech lead would. Then use
  the AI to build exactly that plan. I'll compare what you planned with what got built.
- **Unit tests are expected.** Business logic and data mapping need tests that check
  real outcomes and run green on screen. A session with no tests won't pass.
- **Steer, don't hand-tune.** Read as much code as you like, and I'll ask you to walk me
  through it. When the AI gets something wrong, fix it through the AI (a prompt, a
  rule, your CLAUDE.md), not by editing types, names or formatting yourself.
- **One story at a time.** The product brief is for you and your architecture plan.
  Give the AI stories one at a time, as I give them to you.

**What I don't want to see:** one-shotting a feature, skipping tests, or getting
absorbed in hand-tweaking code.

### What a plan looks like

It can be short. It should be specific enough that I could predict the diff from it:

- the acceptance criteria you'll meet
- the files or modules you'll add or change
- the key types and interfaces
- the unit tests you'll write, by name
- the order you'll have the AI work in
- any product questions for me

---

## Before we start

- Flutter installed and healthy: `flutter doctor` with no blocking issues
- A run target that **keeps local storage between runs**: macOS or Windows desktop, or
  an emulator or simulator that's already booted. (Flutter web debug runs start with a
  fresh browser profile, so saved data disappears.)
- Your AI tools installed and signed in, **set up the way you work every day**. Your
  own skills, plugins, agents and global config are welcome. You'll give me a
  one-minute tour at the start.
- An **empty GitHub repo** you can push to, with me (`jeffhigham-f3`) invited
- Screen share of your whole desktop, with your editor and terminal fonts bumped up
- An email address I can send a file to during the session

If the session uses your own API or subscription tokens, keep track and we'll
reimburse them.

---

## Ground rules

- **Think out loud,** and narrate your tools. When a skill or agent kicks in, tell me
  what it's doing.
- **Ask me product questions.** The stories have gaps, some of them on purpose.
- **Every technical decision is yours.** Tell me your reasoning.
- **There are checkpoints.** I'll call time at each one and we'll move on whether or
  not you're finished. Landing something cleanly, or telling me exactly what's left, is
  part of the job.
- **Copy-paste is fine,** between chats or from anything I share.

## At the end of the session

```bash
git tag live-end
git push --tags
```

Everything up to `live-end` is the interview.

## Optional take-home (up to 2 hours)

If you'd like to keep going afterward, you can. It's optional, it won't count against
you, and it can't replace what we saw live.

- **Cap:** 2 hours of work after `live-end`. Your commit times should show this.
- **Push to the same repo,** with commits after the tag.
- **Include:**
  - `docs/prompts/`: the prompts you sent, from the session and the take-home
  - `docs/plans/`: your plans, including the ones from the session
  - `NOTES.md`, one page or less: what you built after the session, what the AI got
    wrong and how you caught it, and what you'd do next

Good luck — looking forward to building something with you.
