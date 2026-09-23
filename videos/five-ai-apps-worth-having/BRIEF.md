---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Five AI apps, each doing one everyday job for you, are worth having on your phone"
destination: shorts
aspect: 1080x1920
language: en
audience: "everyday phone users curious about AI tools"
length: 45s
angle: listicle
---

## Intent

User ask, verbatim: "Make a 45 seconds video talking about 5 AI apps that are good to have".
A fast, upbeat narrated countdown of five AI apps, one clear job each.

## Notes

- The user skipped the intake questions, so this ran autonomously: vertical short-form, voiceover, one finished video.
- App picks (inferred): ChatGPT, Perplexity, NotebookLM, Otter.ai, Canva. The user can swap any.
- No official logos. App names are set in type, with invented icon-style graphics.

## Customizations

- Pending (user request): add a human presenter via a HeyGen AI avatar reading SCRIPT.md, placed in the lower part of the frame with the app graphics above; keep captions; re-render 1080x1920. Blocked in the first session: the network policy denied api.heygen.com. Needs the domains allowed and HEYGEN_API_KEY set as an environment variable. Still to confirm: male or female presenter, and HeyGen's own voice vs the current Kokoro voiceover.
- Destinations confirmed by the user: TikTok, YouTube (Shorts) and Instagram (Reels).
