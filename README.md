<div align="center">

# 💎 Plumb

**Private, on-device meeting notes for your Mac.**

Record a meeting, get a clean structured summary — without your audio ever
leaving your computer.

[![Download the latest release](https://img.shields.io/badge/⬇_Download-Latest_release-2563eb?style=for-the-badge)](https://github.com/emzcpp/plumb-releases/releases/latest)

*Currently in private beta · macOS (Apple Silicon)*

</div>

---

## 👋 Welcome, tester

Thanks for trying Plumb! This repo is the **download + auto-update channel** for
the app. Grab the latest build below, and from then on Plumb keeps itself up to
date — you won't need to come back here.

## ✨ What Plumb does

- 🎙️ **Records** your meeting — both system audio *and* your microphone.
- 📝 **Transcribes on your Mac** with Whisper. Your audio and transcript **never
  leave the device**.
- 🧠 **Summarizes on demand** into TL;DR, decisions, action items, open
  questions and risks — using your own AI provider key, and only when you click.
- 📚 **Grounds the summary** in your own documents (drop in PDFs / docs) so it
  uses your terminology.
- 🗂️ **Organizes** everything in a searchable library with folders & tags, inline
  transcript editing, and one-click **Markdown export**.

Everything is stored in an **encrypted** database; your API keys live in the
macOS keychain only.

## ⬇️ Install

1. Open the **[latest release](https://github.com/emzcpp/plumb-releases/releases/latest)**
   and download **`Plumb-x.y.z.dmg`**.
2. Open the `.dmg` and drag **Plumb** into your **Applications** folder.
3. **First launch only:** right-click the app → **Open** → **Open** again.
   <br>(macOS shows a warning because this beta isn't notarized yet — this is
   expected and only happens once.)
4. If macOS asks for keychain access, click **Always Allow**.

> Plumb needs **Screen Recording** permission to capture system audio — macOS
> will prompt you the first time you hit record. That's normal.

## 🔄 Updates are automatic

When a new version ships, Plumb notices on launch and shows a small banner —
click **Update & restart** and it updates itself in place. **Your meetings,
settings, and keys are kept.** Each update is cryptographically verified before
it's installed, so you always get a genuine build.

## 🔐 Privacy in one line

Your audio and transcripts stay on your Mac. The **only** time anything leaves is
the summary step — it sends just the transcript text to the AI provider *you*
choose, and only when you explicitly confirm.

## 🐞 Found a bug or have feedback?

You're testing an early build — please tell me what's rough! Reach out directly,
or open an issue on this repo. Crashes, confusing UI, wrong summaries, anything.

---

<div align="center">
<sub>Plumb is a privacy-first, local-first desktop app · built with Rust + Dioxus.</sub>
</div>
