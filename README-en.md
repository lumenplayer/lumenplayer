# Lumen Player

> All your movies & shows, in one app.

Lumen is a cross-platform video-on-demand application that aggregates multiple video sites through a configuration-driven approach. Available on macOS, Apple TV, iPhone, and iPad.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🎬 **Multi-Source Aggregation** | Import subscription sources to consolidate dozens of video sites into one app |
| 🔍 **Smart Search** | Enter keywords to search all configured video sources simultaneously |
| ▶️ **One-Click Play** | Automatically resolves playback links and selects the best route |
| ☁️ **iCloud Sync** | Playback progress and favorites sync across devices automatically |
| 🧩 **Plugin System** | Supports both LumenPlugin and MacCMS direct API video source types |
| 🔒 **Password Protection** | Video sources support password encryption to protect private configurations |
| ⌨️ **Keyboard Shortcuts** | Full keyboard shortcut coverage on macOS |
| 📡 **AirPlay** | Cast your screen to a big-screen TV |

---

## 🚀 Quick Start

### Step 1: Add a Video Source

Open Lumen → Settings (`⌘ ,`) → **Video Sources** tab → **Add Video Source**.

#### Option A: Import via URL

Enter the video source name and subscription JSON URL (must start with `https://`) in the dialog, then click Add.

#### Option B: Import via Passphrase

Type a passphrase (e.g., `alianglaile`) in the URL field—the app will automatically recognize and resolve it to the corresponding subscription source.

### Step 2: Start Browsing

Once added, the app will automatically load the video source. The sidebar displays the current site name; click to switch between sites.

---

## 📺 Recommended Subscription Sources

> The following are community-maintained third-party subscription sources, provided for reference only. Availability depends on your network environment and how actively each source is maintained.

| Maintainer | Source Name | Project / Passphrase | Notes |
|------------|-------------|----------------------|-------|
| **alianglaile** | Test Source | Passphrase `alianglaile` | Includes multiple popular sites |
| **alianglaile** | Mainland Test Source | Passphrase `alianglailecn` | Includes sites accessible in mainland China |
| **alianglaile** | 18+ Test Source | Passphrase `alianglaile18` | Includes adult content sites |
| **Biu** | Paid Source | [Details](https://info.infiniteapi.com/about) | Requires payment |


> [!IMPORTANT]
> We recommend keeping the number of video sites to a minimum—**3–5 high-quality sites is sufficient**. Too many sites will significantly slow down search, since every enabled site is queried simultaneously. You can individually disable unused sites in the video source settings.

> [!TIP]
> 🔌 **Contributions welcome!** To write plugins, see: [lumenplayer/lumenplugin](https://github.com/lumenplayer/lumenplugin)
>
> Lumen is compatible with the [SyncNext](https://github.com/qoli/syncnext-api) video source format.

---

## 📖 Page Overview

| Page | Functions |
|------|-----------|
| 🏠 **Home** | Hero banner carousel, continue watching, favorites, categorized site content |
| 🔎 **Search** | Keyword search + category browsing (with tag filters), search history |
| 📋 **Detail** | Movie info, episode list, source switching, favorites, change source |
| ▶️ **Player** | Full-screen playback with shortcut controls, Picture-in-Picture, speed adjustment |
| 🕒 **Watch History** | History with progress bars, one-click resume |
| ❤️ **Favorites** | Favorites list management, quick access to detail pages |
| ⚙️ **Settings** | Video source management, playback parameters, cache settings |

---

## 📚 Documentation

- 📘 [macOS User Guide](macos-guide.md) — Detailed instructions for each page
- 🔌 [Plugin Development Guide](https://github.com/user/lumenplayer-plugin) — LumenPlugin developer documentation

---

## 🎯 Typical Workflows

### Workflow 1: Browse by Category
```
Search Page → Category Card Wall → Select Category → Browse List (Paginate / Filter) → Click Title → Detail Page → Play Episode
```

### Workflow 2: Keyword Search
```
Search Page → Enter Keywords → Search Results → Click Title → Detail Page → Play Episode
```

### Workflow 3: Home Recommendations
```
Home → Trending Dramas / Movies / Variety Shows → Click Recommendation Card → Detail Page → Play Episode
```

### Workflow 4: Resume Playback
```
Watch History → Click History Entry → Auto-resume (continues from last position)
```

### Workflow 5: Revisit Favorites
```
Favorites → Click Saved Title → Detail Page → Play Episode
```

---

## 🌐 Multi-Platform Support

| Platform | Highlights |
|----------|------------|
| **macOS** | Liquid Glass–style UI, sidebar navigation, full keyboard shortcut coverage |
| **Apple TV** | Big-screen optimized UI, focus engine navigation, Siri Remote control |
| **iPhone (In Development)** | Compact layout, one-handed operation optimized |
| **iPad (In Development)** | Widescreen multi-column layout, Split View multitasking support |

---

## ❓ FAQ

### No Search Results?
- Verify that the video source's `search` field is set to `true`
- Some sites have IP or region restrictions
- Try searching for a well-known title to rule out source-level issues

### Can Search but Can't Play?
- Sources of type `theme` only provide recommendations—clicking will auto-search other playable sources
- Some VIP content may be filtered by the source
- Certain sites require a specific regional IP

### Subscription Source Failed to Load?
- Check whether the subscription URL is accessible
- Confirm the JSON format is correct (non-standard JSON with comments and trailing commas is supported)
- Check your network proxy settings

---

<sub>Lumen is an independently developed video-on-demand application. Users must provide their own legal video content sources; the app itself does not supply any video content.</sub>


---

## 💬 Community & Feedback

Join the Telegram channel for the latest updates, subscription source sharing, and discussion:

👉 [https://t.me/lumenplayer](https://t.me/lumenplayer)

### 📮 Issue Reporting

If you encounter a bug or have a feature suggestion, feel free to submit via GitHub Issues:

👉 [Submit an Issue](https://github.com/lumenplayer/lumenplayer/issues/new/choose)

We provide the following templates—please choose as appropriate:

| Template | Purpose |
|----------|---------|
| 🐛 **Bug Report** | Report app crashes, playback issues, UI errors, etc. |
| ✨ **Feature Request** | Propose new features or improvements |
| ❓ **Question** | Usage questions (please check the FAQ above first) |

> [!TIP]
> When submitting a bug report, providing detailed **reproduction steps**, **system version**, **app version**, and **log screenshots** will greatly speed up issue resolution.
