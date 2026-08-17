# Mobile Code Interview

Welcome, and thanks for taking the time. This repo is intentionally empty — you'll
create the app during the session.

The exercise is **one feature that grows in three rounds**. You'll get each round's
requirements as a user story when we reach it, so there's nothing to read ahead on.
Roughly the first half is hand-written code and the second half is AI-assisted.

---

## Before we start

Please have these ready **before** the call so we don't spend session time on setup:

- Flutter installed and healthy — `flutter doctor` with no blocking issues
- A run target you can launch quickly (see below)
- Network access for `flutter pub get`
- Your AI coding tool of choice installed and signed in
- Screen share ready, with your editor font size bumped up so it's readable

## Setup (we'll do this together at the start)

```bash
git clone <this-repo-url> mobile-code-interview
cd mobile-code-interview

flutter create --project-name tally_app --platforms=web,ios,android .
flutter run -d chrome
```

> **Note the `--project-name` flag** — it's required. This directory has hyphens in
> its name, which aren't legal in a Dart package name, so a bare `flutter create .`
> will fail.

You should land on the standard Flutter counter app. That's our starting point.

### Run target

**Chrome is recommended** — it has the fastest startup and hot reload, which matters
when the clock is running. `macOS` desktop is an equally good choice.

A simulator or physical device is fine if you strongly prefer it, but please have it
already booted before we begin — waiting on a cold simulator boot eats into your time,
not mine.

---

## How we'll work

**Commit each round to its own branch**, so there's a clean record of how the feature
evolved:

```bash
git checkout -b phase-1     # round 1
# ...build, then:
git add -A && git commit -m "Round 1"

git checkout -b phase-2     # round 2, branched from phase-1
```

Don't worry about polished commit messages or squashing. The branches are just so we
can walk through your work afterward.

## Ground rules

- **Use whatever tools you'd normally use.** AI assistants included — I'll tell you
  when each round is meant to be hand-written versus AI-driven, but I'm not going to
  police your editor. I'm more interested in *how* you use your tools than whether you
  avoided them.
- **Think out loud.** I care much more about your reasoning than about finished code.
- **Ask questions.** The requirements have gaps in them. Some of those gaps are there
  on purpose, and noticing one counts for more than guessing well.
- **Don't worry about finishing.** The exercise is deliberately sized so that very few
  people complete every round. Getting partway with clear reasoning beats rushing.

Good luck — looking forward to building something with you.
