# Android_game_AI

<!-- omgithub:readme:start -->
## 🚀 Build, play, and remix with OMGithub

**Remixed using [OMGithub.com](https://omgithub.com).**

[![OMGithub](https://img.shields.io/badge/OMGithub-Open%20project-orange?style=for-the-badge)](https://omgithub.com/Anthonyp707/Android_game_AI)
[![GitHub](https://img.shields.io/badge/GitHub-Source-181717?logo=github&style=for-the-badge)](https://github.com/Anthonyp707/Android_game_AI)

- 🎮 [Open the project](https://omgithub.com/Anthonyp707/Android_game_AI).
- ✨ [Remix this project](https://omgithub.com/?remix=Anthonyp707%2FAndroid_game_AI).
- 💻 [Explore the source](https://github.com/Anthonyp707/Android_game_AI).
- 🛠️ [Check build runs](https://github.com/Anthonyp707/Android_game_AI/actions).
- 🐛 [Report an issue](https://github.com/Anthonyp707/Android_game_AI/issues).
- 👤 [Explore the creator's projects](https://omgithub.com/Anthonyp707).
- 🌍 [Create with OMGithub](https://omgithub.com).
- 🧬 [Explore the remix source](https://github.com/Anthonyp707/Android_game_AI).
<!-- omgithub:readme:end -->

## mori companion

A cozy, responsive AI companion studio with an animated interactive forest spirit, a chat panel, voice playback/input, web search, configurable appearance and personality, and optional one-shot screen/camera snapshots.

### Run locally

Open `index.html` in a modern browser, or serve this folder over HTTP (recommended for camera/screen permissions):

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

### Connect your AI

Open **Personalize → AI connection** and enter an OpenAI-compatible base URL, model name, and API key. The key is kept in `sessionStorage` for this tab, and requests are sent directly from your browser to the endpoint you configured. Your provider must allow browser requests (CORS). Without a configured provider, the built-in demo replies locally. For image understanding, use a vision-capable model and explicitly attach a screen/camera snapshot to a message. Audio playback uses browser speech synthesis; voice input depends on browser speech recognition support.

Screen/camera sharing is opt-in and snapshot-only. This frontend does not record, continuously monitor, bypass provider safeguards, or include free image generation. Provider policies, cost, and capabilities still apply. The 3D-like companion is rendered with animated CSS, so the project has no large external model downloads or tracking scripts.

