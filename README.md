# Muse Ember demo

A motion graphics demo video made with Muse Ember (via OpenRouter) for the Build Day: OpenRouter × Meta hackathon.

- **Demo video**: `renders/muse-ember-demo.mp4` (60s, 1920×1080, H.264 with audio)
- **Brief**: https://app.notion.com/p/openrouter/Build-Day-OpenRouter-x-Meta-4102fd57c4dc808da9c8eaa351d460ad

## What it is

A HyperFrames composition, HTML, CSS and seekable GSAP animations that render to MP4. Voiceover in a Burt Reynolds-style voice via ElevenLabs.

- Entry: `index.html` (1920×1080, 60s, 6 scenes)
- Stack: HyperFrames 0.9.28, GSAP 3.15.0
- Voiceover: ElevenLabs text-to-speech, Burt Reynolds voice (`assets/vo.mp3`)

## Run

```bash
bunx hyperframes check
bunx hyperframes render -o renders/muse-ember-demo.mp4
```

## Model

All sessions run on `meta/muse-ember` through OpenRouter (see `.claude/settings.local.json`).

Sign-off: Karl Villanueva
