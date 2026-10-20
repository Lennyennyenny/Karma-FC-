<div align="center">

# 🌍 🏆 Karma 🏆 🌍

### One command. More football.

A Discord-based platform for competitive **11v11 EA SPORTS FC** football — organised scrims and tournaments, run end to end by a purpose-built bot.

![Status](https://img.shields.io/badge/status-in%20active%20development-orange)
![Built with](https://img.shields.io/badge/built%20with-Python%20%C2%B7%20discord.py-blue)
![Platform](https://img.shields.io/badge/platform-Discord-5865F2)

</div>

---

## What is Karma?

The new FIFA is here, so it's time to get some proper football going.

Karma is a home for players who want more competitive 11v11 — better opposition, and competition that actually means something. It's extra football between your regular fixtures. Not a replacement for your club — a reason to keep playing when you're not in one, or when you've got downtime.

The idea is simple. **One command — `/karma` — and a session goes out across the server.** Players sign up, teams get sorted, you play. Competitive scrims, four-team tournaments, and a steady supply of games against people who can actually play.

A place to mix with players from other clubs, build chemistry, test your level and get more minutes in.

## Our mission

> To build the best place to play competitive 11v11 — and to build it with the players who actually use it.

We're not trying to be another server where anyone can turn up, kick a ball about and call it competitive. We want quality players who want quality games. If you're confident in your ability, enjoy a bit of competition and want to play against people who can actually play, you're in the right place.

**Quality over numbers. Games that mean something. Football that's worth turning up for.**

## What it does

Everything from calling a session to the final whistle runs through the bot:

- **⚽ Sessions in one command** — a host runs `/karma`, and the session goes out server-wide with a live sign-up card.
- **📋 Position sign-ups** — players pick a main and a backup, so captains can build balanced teams.
- **✅ Check-in** — players confirm they're there on the night; anyone who drifts off is handled fairly so spots go to players who actually turn up.
- **🧢 Captains & drafting** — captains are drawn and confirmed by the host, then draft their teams before kickoff.
- **🔊 Matchday voice** — teams are moved into their own voice channels when the draft is done, and tidied away after the game.
- **📊 Stats on the record** — results, Man of the Match and player stats are tracked, game after game.
- **📈 Levels** — the more you play, the more you level up, with your record travelling with you.
- **🛡️ Verification & onboarding** — new members are welcomed and verified, and nudged to pick their positions so they're ready to play.
- **📰 EA news** — a companion feed posts EA SPORTS FC news, Pitch Notes, playtests and sales into the community.

See **[docs/features.md](docs/features.md)** for the full picture, and **[docs/how-it-works.md](docs/how-it-works.md)** for a walk through a matchday.

## Under the hood

Karma is built from scratch for the community that uses it.

- **Python · discord.py · SQLite.**
- **Event-driven** — a single slash-command entry point, background schedulers handling everything that happens on a clock (check-in windows, kickoffs, reminders), and interactive panels that keep working across restarts.
- **Modular** — each feature is self-contained, so the platform grows without disturbing what already works.
- **Built to be reliable** — automated pre-release checks and a safe backup-and-restart routine, so sessions, sign-ups and stats carry on through updates.

> This repository is the public home and documentation for Karma. The bot's source is kept private.

## Project status

We're early, and that's deliberate. The server is fresh, the bot is being built from scratch, and the format is still taking shape.

The big decisions — how teams get picked, how results are confirmed, how stats and Man of the Match should count — are being made **with** the players who'll use it, not guessed from behind a keyboard. Things might wobble. That's the point of getting in early: we want to find what doesn't fit, with the players, before it gets serious.

See the **[roadmap](docs/roadmap.md)** for where it's heading.

## Who's it for?

Players who want quality games and take their football seriously — without it being a second job. If you want proper, competitive 11v11 between your club fixtures, you'll fit right in. If you're after a kickabout, this probably isn't the one.

---

<div align="center">

🏁 **One command. More football.**

See you on the pitch.

</div>
