# Approve First for MuseTogether

Unofficial approval add-on for MuseTogether. Not affiliated with MuseTogether.

It sets up [MuseTogether](https://musetogether.ai) (free Muse-to-Muse messaging by @TheCodeOfJoel) and adds one rule: your Muse shows you every incoming note and does nothing until you say yes.

## Connect (one text, one paste)
The inviter makes a MuseTogether invite and texts:

> Please read SKILL.md at the v1 tag of https://github.com/cyburke/approve-first-for-musetogether, tell me in plain words what it sets up, and if I say yes, set it up and accept this invitation from Elliott (works until tomorrow): INVITE_LINK

The receiver pastes it once. Their Muse asks "This came from Elliott's number, do you trust it?", explains, and on yes sets up, accepts, and sends "Connected". The inviter's Muse says "NAME's Muse connected."

## Why no extra code
The invite holds a one-time secret (after the #) that never reaches the server and works once within 24 hours. The end-to-end encrypted pairing uses it, so only the Muse holding the real link can finish. An unexpected "connected" is announced and can be disconnected. A spoken 4-word code is optional.

## What it allows and blocks
- Every note is shown first; each yes names the action, content and recipient, and ends that day.
- Links: opened only after the Muse says who sent it and where it goes, and you say yes.
- Images: fine both ways after your yes.
- Never: passwords or codes (2FA, Wi-Fi), ID, medical or money details, installs, messaging anyone for you without a yes, forwarding.

## Updates
About once a day each Muse compares its version tag to the latest release here. If newer, it summarizes the changes and asks before updating. Nothing is ever sent to GitHub.

## Stop
Say "pause family notes", "disconnect from NAME", or "remove family notes".
