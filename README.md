# Gator-Wire

The shared Car 5 wiring project for UF Solar Gators.

This repository holds the project that the whole team edits together in
**GatorWire**. Open the app, connect it to this repository, and everyone
works on the same wiring at the same time. Your changes save on their own,
and teammates' changes show up within about half a minute.

**Open the app:** https://solar-gators.github.io/Custom-Apps/gatorwire

> You don't need to edit anything in this repository by hand. The app
> creates and updates `project.json` for you, and every save shows up here as
> a commit with the saver's name on it.

---

## Getting started

Do this once on each computer you use. It takes about five minutes.

### 1. Make your token

The token lets the app save to this repository as you.

1. Go to **[github.com/settings/personal-access-tokens/new](https://github.com/settings/personal-access-tokens/new)**.
2. **Token name:** `GatorWire`.
3. **Expiration:** pick a date at the end of the semester.
4. **Resource owner:** `Solar-Gators`.
5. **Repository access:** choose **Only select repositories**, then pick **Gator-Wire**.
6. **Permissions:** open **Repositories**, find **Contents**, and set it to **Read and write**.
7. Click **Generate token** and copy it. It starts with `github_pat_`.

If `Solar-Gators` isn't in the Resource owner list, ask an admin to add you to
the organisation first.

### 2. Connect the app

1. Open **https://solar-gators.github.io/Custom-Apps/gatorwire**.
2. At the top right of the header, click **In this browser · Share**.
3. **Repository:** `Solar-Gators/Gator-Wire` (already filled in).
4. **File in the repository:** `project.json` (leave as is).
5. Paste your token and click **Connect**.

The Car 5 project opens, and the header now says **Shared · up to date**.

Your token stays in your browser. It is never saved in the page or in this
repository. Don't paste it anywhere else, and never commit it.

---

## Working on the project

There's no save button to remember. Just work.

- **Your edits save on their own** about 10 seconds after you stop. To save
  right away, click the status in the header, then **Save now**.
- **Teammates' changes appear on their own.** You'll see a short message like
  *"Brought in 2 changes from a teammate."*
- **If you both changed the same thing,** a window shows your version and
  theirs. Pick one for each, then click **Keep these**.
- **If someone changed the drawing,** a banner says so. Finish what you're
  doing, then click **Apply and reload**.

Use one tab per person. Two tabs in the same browser share one copy.

### What the header status means

| Status | What it means | What to do |
| --- | --- | --- |
| **Shared · up to date** | Everything is saved. | Nothing. |
| **Shared · saving soon** | You have edits that save in a few seconds. | Nothing. Wait before closing the tab. |
| **Shared · saving…** | Saving now. | Nothing. |
| **Shared · needs a decision** | You and a teammate changed the same thing. | Pick which version to keep. |
| **Shared · drawing updated** | A teammate changed the drawing. | Click **Apply and reload** when ready. |
| **Shared · read-only** | No token is connected, so you can look but not save. | Click the status and add your token. |
| **Shared · not synced** | Something went wrong. | Hover over it to see why. |

---

## Problems

**"GitHub did not accept the token."** It has expired or was typed wrong. Make
a new one (step 1), click the status in the header, paste it under
**Replace token**, and click **Use this token**.

**"GitHub would not let this token save the project."** The token is missing a
permission. Check that it has access to **Gator-Wire** and that **Contents** is
**Read and write**.

**"The rate limit was reached."** This only happens without a token. Add one.

**I want a backup.** Click **Save file** in the app at any time. You can also
download any earlier version of `project.json` from this repository's commit
history.

**I want to stop sharing on this computer.** Click the status in the header,
then **Stop sharing here**. Tick **also forget my token** if it's a shared
computer.

---

## The other version: working on your own

GatorWire also works with no GitHub connection at all. This is useful for
trying things out without changing the team's project, or for working
offline.

**https://solar-gators.github.io/Custom-Apps/gatorwire**

Open it without clicking **In this browser · Share**, and your work stays on your
computer only. Use **Save file** to keep it and **Open file** to pick it up
again. Nothing you do there reaches this repository.

To bring your own work into the shared project, talk to the team first.
Opening a file while connected stops sharing on that computer, so it can't
overwrite everyone's work by accident.

---

## For whoever maintains this

- The app itself lives in
  [Solar-Gators/Custom-Apps](https://github.com/Solar-Gators/Custom-Apps).
  This repository only holds the data.
- Keep this repository **public**. Anyone can read the wiring without a
  token, but only people with a token can save.
- Don't turn on GitHub Pages here. Every save is a commit, and Pages would try
  to rebuild on each one.
- To remove someone's access, remove them from the organisation. Their token
  stops working.
