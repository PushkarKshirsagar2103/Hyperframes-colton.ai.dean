<!-- HYPERFRAMES_SETUP_INCOMPLETE -->
<!-- ^ Leave this marker until /setup is complete. It tells Claude to greet a new user
     and run onboarding before any video work. The setup skill removes it when finished.
     Remaining setup steps: reference reels (Step 3) and brand colors (Step 4). -->

# Creator Profile — PovPushkar

Your identity, positioning, and workflow for video work in this workspace. **Read this before every video task** (alongside `PREFERENCES.md`). Use it for on-screen text, niche framing, and workflow assumptions.

## Identity

- **Name on-screen**: PovPushkar
- **Instagram**: @povpushkar
- **TikTok**: —
- **YouTube**: Pov Pushkar (channel name)
- **X / other**: —

When putting handles on-screen (lower-thirds, outros, end-cards), use the platform-appropriate handle: `@povpushkar` on Instagram Reels versions, `Pov Pushkar` on YouTube Shorts versions. Spell both exactly as written here.

## Platform priority

**Instagram Reels + YouTube Shorts, equal priority** (cross-post both). Default format: **9:16 vertical, 1080×1920, 30fps**. Keep captions and key graphics inside the safe zone so neither app's UI (likes, comments, description) covers them.

## Content niche

Tech, specifically:

- Tech gadgets and product reviews
- AI tools
- Useful websites
- Tech tips
- Comparisons (product vs. product)
- Gaming

When planning a new video, assume this niche unless told otherwise.

## On-camera mix

**Both.** Mainly **talking-head** footage, supported by B-roll, product shots, screen recordings, and motion graphics where they fit.

- **Face-cam** → use `/short-form-video` face-mode choreography (BOTTOM / FULLSCREEN modes).
- Product shots and screen recordings are the main B-roll. Use them for demos, specs, websites, and app walkthroughs.

## Workflow — division of labor

**The assistant handles the editing.** PovPushkar supplies raw talking-head footage, B-roll, product shots, and screen recordings. The assistant:

- **Cuts the raw footage**: removes long pauses, dead air, repeated or unnecessary takes, and false starts.
- **Preserves natural delivery**: keep the original voice, rhythm, and natural **Hinglish** (Hindi + English) speech. Don't over-tighten cuts into a jumpy, robotic feel, and never replace or re-voice the audio.
- **Adds the visual layer**: captions, B-roll, clean transitions, and occasional motion graphics.

This overrides the workspace default of "never cut the speaker's audio". Here, cutting dead air and bad takes is expected. Changing what was said, or its meaning, is not.

PovPushkar is a beginner and does not write code or configure tools. Keep every step plain-language, and ask before anything technical.

## Brand identity

- **Look**: premium, clean, modern, minimalist, Apple-like.
- **Text**: white.
- **Accent**: electric lime. Use it tastefully for highlights, never as a large fill.
- Background color and display font are confirmed in setup Step 4 and live in `assets/brand-tokens.css`.

Full editing taste lives in `PREFERENCES.md`.

## Inspiration creators

_(Studied creators live in [`_reference/creator-library/`](_reference/creator-library/). Paste a TikTok / Instagram Reel / YouTube Short URL and run `/study-creator <url>` to add one. At build time, name a creator — "build this like @handle" — to apply their style fingerprint to the visual layer.)_

PovPushkar's reference videos define the editing style, pacing, captions, and motion graphics they like. These are being collected in setup Step 3.

## Posting cadence & length defaults

- _Cadence_: _(TBD)_
- _Default length_: 15–45s short-form vertical is a common sweet spot. Adjust per video (reviews and comparisons may run longer).
- _Default fps_: 30 (matches Instagram + YouTube Shorts defaults).

## Project slug convention

**Topic-only, kebab-case.** Each video gets a new subfolder under `video-projects/<topic-slug>/`. Examples: `iphone-vs-pixel`, `ai-tool-of-the-week`, `useful-websites-part-1`. Keep slugs short and descriptive, so they're easy to scan in `ls video-projects/`.

---

*This file is updated as your creator profile evolves. Major changes (new handles, platform shifts, workflow changes) can be edited here directly.*
