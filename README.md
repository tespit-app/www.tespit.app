[![Tespit Demo](https://github.com/tespit-app/.github/raw/main/assets/demo.gif)](https://github.com/tespit-app/.github/raw/main/assets/demo.gif)

tespit
======

**AI-powered UI bug detection for macOS — entirely on-device.**

[Website](https://tespit.app) • [Privacy](https://tespit.app/privacy) • [Support](https://tespit.app/support)

---

Tespit captures your screen, detects layout issues using Apple Vision + on-device LLMs, and generates structured Markdown bug reports. **No data ever leaves your Mac.**

### How it works

```
Screen Capture  →  Vision Detection  →  On-Device Reasoning  →  Bug Report
```

1. **Capture** — select a region or entire window via ScreenCaptureKit
2. **Detect** — identify UI elements, text, frames, and overlaps with Apple Vision
3. **Reason** — analyse layout issues using Apple Intelligence (FoundationModels) on-device
4. **Report** — generate a structured Markdown bug report with severity ratings

### Features

- 🔒 **100% on-device** — no cloud calls, no telemetry on your screen content
- 🧠 **Apple Intelligence** — leverages FoundationModels for reasoning (graceful fallback on older systems)
- 📸 **Flexible capture** — region selection or full window capture
- 📋 **One-click export** — copy reports or generate bugfix prompts for your AI coding assistant
- ⚡ **Built with Swift 6** — strict concurrency, modern async/await throughout

### Requirements

| | |
|---|---|
| Minimum | macOS 15.0+ |
| Apple Intelligence | macOS 26+ _(optional — deterministic fallback on older systems)_ |

### Coming soon

🍎 Mac App Store — _stay tuned_

---

Built with [SwiftEnsemble](https://github.com/tespit-app/swift-ensemble) — a Swift-native framework for orchestrating on-device ML pipelines.
