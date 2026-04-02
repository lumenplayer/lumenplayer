# Lumen macOS User Guide

[简体中文](macos-guide-cn.md) | [繁體中文](macos-guide.md)

> This guide provides a detailed overview of each page's features and how to use them in Lumen for macOS.

---

## Table of Contents

- [Initial Setup](#initial-setup)
- [Sidebar Navigation](#sidebar-navigation)
- [Home](#home)
- [Search](#search)
  - [Category Browsing](#category-browsing)
  - [Keyword Search](#keyword-search)
- [Detail Page](#detail-page)
- [Player](#player)
- [Watch History](#watch-history)
- [Favorites](#favorites)
- [Settings](#settings)
- [Keyboard Shortcuts](#keyboard-shortcuts)

---

## Initial Setup

### Adding a Video Source

After launching Lumen for the first time, you need to add at least one video source before you can start browsing.

1. Open **Settings** (Menu Bar → Lumen → Settings, or shortcut `⌘ ,`)
2. Switch to the **Video Sources** tab
3. Click the **"Add Video Source"** button in the top-right corner
4. Fill in the dialog:
   - **Source Name** (required): Give the source a name for easy identification
   - **URL or Passphrase**: Enter the subscription HTTPS URL, or type a passphrase directly (e.g., `alianglaile`)
5. Click **"Add"**

> **💡 Tip**: Passphrases are a shortcut. For example, entering `alianglaile` will cause Lumen to automatically resolve it to the corresponding subscription URL—no need to look up the address manually.

Once added successfully, Lumen will automatically download and parse the configuration, and the sidebar will display the current site name.

### Managing Multiple Sources

- You can add multiple video sources, each containing several sites
- In the Settings page, you can **enable/disable**, **edit**, or **delete** each source
- Individual sites within a source can also be enabled or disabled independently
- Click the 🔄 button to check the availability of each site (green = OK, red = error)

---

## Sidebar Navigation

Lumen for macOS uses a classic sidebar + content area layout.

The sidebar contains the following navigation items:

| Item | Icon | Function |
|------|------|----------|
| **Site Name** | — | Displays the current site; click to open the site switcher |
| **Search** | 🔍 | Keyword search and category browsing |
| **Home** | 🏠 | Recommended content and categories for the current site |
| **Watch History** | 🕒 | Viewing history and resume playback |
| **Favorites** | ❤️ | List of favorited titles |

### Switching Sites

1. Click the site name at the top of the sidebar
2. Select the desired site from the popup list
3. The Home and Search pages will automatically refresh with the new site's data

---

## Home

The Home page is the default content page when you open Lumen, showing recommended content from the current site.

### Hero Banner Carousel

- A full-width Hero Banner at the top of the page auto-rotates through recommended titles
- Each card displays the title poster, name, and other information
- Click a banner card to go directly to the title's detail page

### Continue Watching

- If there are unfinished titles, the Home page displays a "Continue Watching" row
- Each card shows the title poster and a playback progress bar
- Click to resume from where you left off—no need to search manually
- If the original site is unavailable, Lumen will automatically search other available sites

### Favorites

- The Home page also displays recently favorited titles
- Click a favorites card to enter the title's detail page

### Category Content

- Below the main sections, the Home page shows categorized content from the current site (e.g., Movies, TV Series, Variety Shows, Anime)
- Each category is displayed as a horizontally scrollable row; use mouse wheel or trackpad to scroll
- Click **"More"** on the right side of a row header to jump to the corresponding category list on the Search page
- Click a title card to enter the detail page

### Theme Source

If the current site is a **theme source**, it only provides recommendation information and does not directly offer playback links. After clicking a title card from a theme source, Lumen will automatically search other playable sites for the playback link.

```
Home → Click theme source recommendation → Auto-search playable sites → Detail Page → Play
```

---

## Search

The Search page is the most frequently used page in Lumen, combining **keyword search** and **category browsing** in one place.

### Search Bar

- Located in the top toolbar
- Enter keywords and press **Return** to search
- Click the ✕ button on the right side of the search bar to clear the search and return to the browsing view

### Search History

- When no search term is entered, a "Recent Searches" horizontally scrollable row appears at the top
- Each history card shows the search term and a cover thumbnail
- Click any history card to re-run that search
- Click **"Clear"** in the top-right corner to clear all search history

---

### Category Browsing

Below the search area, the page displays category cards for the current site.

#### Category Card Wall

- Each category is shown as a poster cover card (e.g., "Movies," "TV Series," "Variety Shows," "Anime")
- Cards use gradient colors to distinguish categories, with scale and highlight effects on hover
- Click a category card to enter that category's content list

#### Category Content List

After entering a category, the page content switches to the title list for that category:

1. **Category name at the top**, with a back button in the upper-left corner
2. **Tag filter bar** (if the category has configured tags):
   - Tags are arranged horizontally, e.g., "All," "Mainland," "Hong Kong/Taiwan," "Japan/Korea," "Western"
   - Click a tag to filter content
3. **Title grid**:
   - Displays all titles in the category as a poster card grid
   - Each card shows cover art, name, and rating
   - Scrolling to the bottom automatically loads more
   - You can also click the "Load More" button to load manually
4. **Click a title card** → Enter the detail page

```
Search Page → Category Card Wall → Select Category → Tag Filter → Browse Title List → Click Title → Detail Page → Play
```

---

### Keyword Search

1. Enter a title name or keyword in the search bar
2. Press **Return** to search
3. Lumen sends requests to all enabled sites that support search simultaneously
4. A loading indicator is shown during the search; results are appended to the page in real time
5. Results are displayed as a poster card grid, showing the total number of titles found
6. Each card displays the site name for easy source identification
7. Click a title card to enter the detail page

```
Search Page → Enter Keywords → Return to Search → Search Results Grid → Click Title → Detail Page → Play
```

---

## Detail Page

The detail page shows complete title information and playback entry points, featuring an Apple TV–style immersive design.

### Top Hero Area

- **Full-width background image**: Prioritizes landscape stills; falls back to a blurred cover image when unavailable
- **Title**: Large bold text with shadow effect
- **Metadata badges**: Capsule-shaped badges showing genre, year, region, and rating
- **Favorite button**: Click the ❤️ badge to add/remove the title from favorites
- **Synopsis**: Title description; click "More" to expand the full info popup
- **Cast & Crew**: Director and lead actors shown on the right side

### Source Switching

- If a title has multiple playback sources (Flags), a "Sources" switcher bar is displayed
- All available sources (e.g., "Quantum," "Lightspeed," "Flash") appear as a button group
- Click a different source name to switch the episode list

### Episode List

The episode list automatically selects the appropriate display style based on the content:

#### Card-Style Episodes (with Thumbnails)

- When episodes have thumbnails, they are displayed as large horizontally scrollable cards
- Each card includes: episode thumbnail, episode number label, episode name, and synopsis
- The currently playing episode is highlighted with a white border

#### Compact Episode Grid

- When episodes have no thumbnails, they are displayed as a compact grid
- Each button shows the episode name
- The currently playing episode is highlighted in brand color with a play icon
- Buttons use a liquid glass effect

### Playback

1. Click any episode to start playing
2. A "Resolving playback URL…" loading state is shown before playback
3. Once resolved successfully, the player opens automatically

### Alternative Sources

- An "Alternative Sources" section is displayed at the bottom of the page
- Lumen automatically searches other sites for the same title
- Results are shown as horizontally scrollable poster cards with the site name displayed
- Click an alternative source card to switch to that site's detail and episode info

> **💡 Use Case**: When a site's playback link is broken, use alternative sources to find other available sites.

---

## Player

Click an episode to enter the full-screen player.

### Playback Controls

- **Play/Pause**: Click the center of the screen or press `Space`
- **Fast Forward/Rewind**: Press arrow keys `←` `→` (default 10 seconds; adjustable in Settings)
- **Seek**: Drag the progress bar at the bottom
- **Volume**: Use system volume keys
- **Playback Speed**: Supports 0.5x–2.0x
- **Picture-in-Picture**: Click the PiP button to watch while doing other things

### Auto Resume

- Your viewing progress is saved automatically
- Opening the same episode again will resume from where you left off

### Auto Play Next Episode

- When the current episode finishes, the next episode plays automatically (can be disabled in Settings)

---

## Watch History

The Watch History page records all titles you've watched.

### History Cards

- Displayed as a 5-column poster grid
- Each card shows:
  - Title cover art
  - **Playback progress bar** (a blue bar at the bottom showing viewing progress)
  - Title name
  - Site name and episode info

### One-Click Resume

- Click any history card to resume from your last position
- A loading overlay appears on the card during loading
- If the original site is unavailable, Lumen will automatically search other available sites

### Managing History

- **Delete individual entry**: Right-click a history card → Select "Delete"
- **Clear all**: Click the "Clear History" button in the top-right corner; requires confirmation

```
Watch History → Click History Card → Auto-resume (continues from last position)
```

---

## Favorites

The Favorites page manages all your favorited titles.

### Favorites List

- Displayed as a 5-column poster grid
- Shows title cover art, name, and rating badge
- Total favorites count is shown at the top

### Sort Options

- **Date Added** (default): Sorted by most recently added
- **Name**: Sorted alphabetically by title name
- Switch via the sort selector in the top-right corner

### Actions

- **View details**: Click a favorites card → Enter detail page → Select episode to play
- **Remove from favorites**: Right-click a favorites card → Select "Remove from Favorites"

### How to Favorite a Title

On the detail page, click the **❤️ Favorite** button in the metadata badge row. Once favorited, it syncs to your other devices via iCloud.

```
Favorites → Click Favorited Title → Detail Page → Select Episode to Play
```

---

## Settings

Open via Menu Bar → Lumen → Settings (`⌘ ,`).

### General Settings

| Option | Description | Default |
|--------|-------------|---------|
| Default Speed | Default playback speed | 1.0x |
| Skip Forward/Back Duration | Seconds to skip with arrow keys | 10 seconds |
| Auto Play Next Episode | Automatically play the next episode | On |
| Appearance | Follow System / Dark / Light | Follow System |

### Video Source Management

The Video Sources tab provides full source management:

| Action | Description |
|--------|-------------|
| ➕ **Add** | Add a new video source via URL or passphrase |
| ✏️ **Edit** | Modify a source's name or URL |
| 🗑️ **Delete** | Remove a video source and all its associated sites |
| 🔄 **Check** | Test the availability of each site within a source |
| 🔒 **Encrypt** | Set password protection for a video source |
| 🔛 **Enable/Disable** | Toggle the enabled state of a source or site |

Expanding a source reveals all its contained sites, including:
- Site name, priority, type (Plugin / Direct API / Theme)
- Check status (green/red indicator)
- Notes
- Per-site enable/disable toggle

### Advanced Settings

Advanced settings provide fine-grained cache duration controls:

| Cache Type | Description | Default |
|------------|-------------|---------|
| Home Cache | Home page content cache duration | 4 hours |
| Home Banner Cache | Hero Banner cache duration | 48 hours |
| Category List Cache | Category list cache duration | 7 days |
| Category Content Cache | Title list within a category | 4 hours |
| Detail Page Cache | Title detail page cache | 1 hour |
| Completed Content Cache | Cache for finished titles | 7 days |
| Plugin Engine Cache | Plugin script cache | 4 hours |

- Click **"Clear All Cache"** to free all storage used by caches
- Cache duration changes only apply to newly written cache entries

---

## Keyboard Shortcuts

| Shortcut | Function |
|----------|----------|
| `⌘ ,` | Open Settings |
| `Space` | Play / Pause |
| `←` `→` | Rewind / Fast Forward (default 10 seconds) |
| `Return` | Start Search |
| `Esc` | Exit Player |

---

## Full Workflow Diagram

```
                        ┌──────────────┐
                        │  Add Video   │
                        │   Source     │
                        │(Settings → Sources)│
                        └──────┬───────┘
                               │
                    ┌──────────┴──────────┐
                    ▼                     ▼
              ┌──────────┐         ┌──────────┐
              │   Home   │         │  Search  │
              └─────┬────┘         └─────┬────┘
                    │                    │
         ┌──────┬──┴──┐          ┌──────┴──────┐
         ▼      ▼     ▼          ▼             ▼
      Banner Continue Category  Keyword     Category
      Recs   Watching  Rows    Search      Browsing
         │      │     │      ──────────    ────────
         │      │     │      Results Grid  Tag Filter
         │      │     │          │         Title List
         ▼      ▼     ▼          ▼             ▼
      ┌──────────────────────────────────────────┐
      │             Detail Page                   │
      │  Background · Metadata · Favorite · Sources│
      │  Episode List · Alternative Sources        │
      └─────────────────┬────────────────────────┘
                        ▼
                  ┌──────────┐
                  │  Player  │
                  │ Auto-save │
                  │ Progress │
                  └──────────┘
                        │
               ┌────────┴────────┐
               ▼                 ▼
         ┌──────────┐     ┌──────────┐
         │  Watch   │     │ Favorites│
         │ History  │     │  Quick   │
         │ Resume   │     │  Access  │
         └──────────┘     └──────────┘
```

---

<sub>This document applies to Lumen for macOS v1.0.</sub>
