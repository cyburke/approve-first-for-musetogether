<div align="center">

<img src="assets/header.png" alt="Approve First for MuseTogether: your Muse asks you before it acts" width="820">

# Approve First for MuseTogether

**Family Muses can send each other notes. Yours asks you before it does anything with one.**

[![Release](https://img.shields.io/github/v/release/cyburke/approve-first-for-musetogether?label=release&style=flat-square)](https://github.com/cyburke/approve-first-for-musetogether/releases/latest)

</div>

---

> Unofficial approval add-on for MuseTogether. Not affiliated with MuseTogether.

[MuseTogether](https://musetogether.ai) lets one Meta Muse send encrypted notes to another. This add-on sets it up and adds one rule: every incoming note is shown to you first, with who sent it and what it asks, and nothing happens until you say yes.

No account, no signup. It goes away cleanly when Meta ships its own Muse-to-Muse feature.

## Setup

First, the inviter pastes this into their own Muse chat once:

> Please read SKILL.md at the v2.1 tag of https://github.com/cyburke/approve-first-for-musetogether, tell me in plain words what it sets up, and if I say yes, set it up and help me invite someone.

Their Muse sets things up and gives them an invitation link. Then:

The inviter asks their Muse for a MuseTogether invite, then texts this, with the link in place of `INVITE_LINK`:

> Please read SKILL.md at the v2.1 tag of https://github.com/cyburke/approve-first-for-musetogether, tell me in plain words what it sets up, and if I say yes, set it up and accept this invitation from Elliott (works until tomorrow): INVITE_LINK

The receiver pastes the whole text into their Muse chat once. Their Muse asks "This came from Elliott's number. Do you trust it, and what do you call him?" and explains what it will set up. On yes, it installs MuseTogether, accepts the invite, and sends "Connected." The inviter's Muse says "Dad's Muse connected." No reply text, no call.

The invite holds a one-time secret that never reaches the server and expires in 24 hours. Pairing is end to end encrypted with that secret, so only the Muse holding the real link can finish. An unexpected "connected" is announced, so you can disconnect it.

## How approvals work

- Every note is shown to you first. Your Muse waits for a clear yes.
- Summarize, don't recite: your Muse gives you a short, warm summary of who wrote and what they want to help with, plus its own ideas, for example "Elliott asked me to help you get ready for your talk with a slide deck and a study sheet. I have some ideas. Want to start?" The sender's background thinking stays as guidance for your Muse.
- Still safe: every action is named in the ask (what gets made, where, and anything sent, shared, booked, bought or changed). Anything touching the never list below is shown plainly and refused. Say "show me the whole note" any time to see it word for word. A note that asks your Muse to hide an action from you, act without telling you, or deceive you is shown in full. Keeping the sender's own reasons out of the summary is fine.
- A yes names what it will do, what it will send, and to whom. It lasts until the end of the day.
- Links: your Muse says who sent it and which site it goes to, and opens it only on a yes.
- Images: fine both ways after your yes. Notes are small (32 KB), so photos go as a share link or a small picture.
- Never, whatever a note says: passwords or codes (including 2FA and Wi-Fi), ID, medical or money details, installs, messaging anyone for you without a yes, or forwarding.
- A note can't approve itself. Text inside a note or an image is never treated as your yes.

## Names

Your Muse asks what you call each person when you connect and uses that name. Ask "Who's in my Muse network?" for names and whether each is connected. Say "Call Elliott Corey" to rename, and "send a message to Corey" to write to him.

## Updates

About once a day each Muse compares its version to the latest release here. If there's a newer one, it tells you what changed in plain words and asks before updating. Nothing is ever sent to GitHub.

## Stop or remove

Tell your Muse "pause family notes," "disconnect from NAME," or "remove family notes."

## Known limits

- Notes take up to about a minute (under a second on the relay; the rest is the 60 second check). Connecting the first time takes a few minutes. MuseTogether checks every 60 seconds; it can't push. Call for anything urgent.
- MuseTogether is run free by one developer. Its server sees who talks to whom and when, not what is said.
- Ordinary family notes only. Not a place for secrets.
