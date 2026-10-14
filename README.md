# TensionFour

Four-bar tension-hold desk for bedroom producers and AI-music finishers.

AI tools and loop DAWs slam sections together. Session players hold a bass pedal while the harmony moves above it for four bars, then release into the next section.

Live samples only — FluidR3 acoustic grand, upright bass, nylon guitar, trumpet, violin, and an acoustic kit from the PreEight sample CDN pinned to commit `d58301e4a494555f411a2afbc448b724136eee76`.

No oscillators. Audio never leaves the tab.

## Distinct from yesterday and the rest of the line

| Tool | Job |
| --- | --- |
| TagFour | Four-bar last-line tag |
| ModEight | Last-chorus key change |
| LiftTwo | Two-bar pre-hook lift |
| PreEight | Eight-bar pre-chorus climb |
| AfterHook | Eight bars after the hook |
| EndEight | Last eight bars |
| LastHook | Money chorus |
| **TensionFour** | Four bars of pedal hold while harmony moves, then release |

Yesterday's ship was the previous arrangement desk. TensionFour is the missing held tension that makes the next section land.

## Pricing recommendation

One-time **$29** on Lemon Squeezy (mirror on Gumroad) for a future gated build.  
Do not subscribe. Forge Pass stays the recurring cloud bundle. This is a finite desk.

**Current app is free.** No license gate. MIT. A priced build would need a Lemon Squeezy or Gumroad key check.

## Samples

Pinned commit SHAs only. Never @main or @gh-pages.

## Export

Default bounce is 48 kHz, 24-bit stereo.

At 92 BPM and 8 bars the loop file is exactly 1,001,739 samples (`Math.round(8 * 4 * 60 / 92 * 48000)`), first downbeat at sample 0. Tail folded for seamless loop. Peak ≤ −1 dBFS.

Filenames: `tensionfour-recipe-<bpm>bpm-<key>.wav` and matching `.mid`.

## License

MIT. workinwithai-create.
