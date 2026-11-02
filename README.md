<div align="center">

<img src="logo.png" alt="Music DJ Bot Logo" width="140" />

# Music DJ Bot for Discord

**Studio-quality music discovery, interactive Song Cards, and live Voice Radio for your Discord server.**

[![Add to Discord](https://img.shields.io/badge/➕_Add_to_Your_Discord_Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1565796454037979226)
[![Support on Ko-fi](https://img.shields.io/badge/💳_Unlock_Server_Pro_($5)-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/musicdjbot)
[![Pay with Crypto](https://img.shields.io/badge/⚡_Unlock_with_Crypto_($4)-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)](https://coinos.io/musicdjbot)

</div>

---

## Why Music DJ Bot?

Most Discord music bots force everyone into a voice channel just to hear a song, break constantly, or flood your chat with low-quality reuploads, gaming clips, and 3-hour mixes. **Music DJ Bot** is built differently:

- **Play Directly in Text Chat — Or Stream Live in Voice**: Every track posts a clean, playable **Song Card** right in your channel so members can listen inline at their own pace *or* stream together in Voice.
- **One-Click DJ Deck**: Skip tracks (`⏭️`), build a similarity radio station (`👍`), spin the genre wheel (`🎲`), or toggle hands-free Autoplay (`📻`) with a single click—no typing required.
- **Real Music Discovery**: Powered by multi-source music catalog intelligence. Discover top hits, deep subgenres, full artist catalogs, or songs that sound just like your favorite track.
- **100% Studio Music Guarantee**: Automatically blocks short-form clips (<65s), livestreams, gaming videos, vlogs, tutorials, reaction videos, and 3-hour mixes. Only real studio tracks between 65 seconds and 15 minutes get through.
- **Dedicated Voice Channel Streaming**: Crystal-clear voice channel playback with automatic track progression and queue management.

---

## Quickstart: How to Use It in 30 Seconds

Just type `/` in any Discord channel where the bot has access. Many commands include **instant autocomplete menus** so you don't even have to type.

### 1. Discover Top Hits or Any Genre (`/play`)
- **Top Hits**: Type `/play` and press **Enter** (leave `query` blank) to play today's trending music.
- **Pick a Genre**: Click `query` to choose from presets like `🎲 Random Genre`, `🔥 Top Hits`, `🎸 Rock`, `🪩 House`, `🎷 Jazz`, or type **any** genre or subgenre:
  - `/play query: synthwave`
  - `/play query: 90s hip hop`
  - `/play query: liquid drum and bass`

### 2. Play a Specific Song or Direct Track Link (`/play`)
- **By Song & Artist**:
  - `/play query: Harder Better Faster Stronger by Daft Punk`
  - `/play query: Kavinsky - Nightcall`
- **By Supported Music Link**:
  - Paste any supported song URL directly into `query`.
  - *(The bot automatically verifies that the link is a real studio song between 65 seconds and 15 minutes, then queues up similar tracks for your next skip.)*

### 3. Play an Artist's Best Tracks (`/artist`)
- `/artist name: Daft Punk`
- `/artist name: Fleetwood Mac`

### 4. Start a "Similar Songs" Radio Station (`/similar`)
Love a track's vibe and want more like it?
- `/similar song: Nightcall artist: Kavinsky`
- Or simply click the **`👍` (Like)** button under any Song Card in chat.

### 5. Load a Music Playlist (`/playlist`)
Bring your own public or unlisted playlist URLs into Discord with optional **Shuffle** and **Loop** modes:
- `/playlist url: <playlist-url> shuffle: True loop: False`

---

## Interactive Song Card Controls

Every song posted by Music DJ Bot comes with 4 interactive controls underneath the player:

| Button | Name | What It Does |
| :---: | :--- | :--- |
| **`⏭️`** | **Next Track** | Instantly skips to the next pre-loaded song in your current genre, playlist, artist, or similarity session. |
| **`👍`** | **Like / More Like This** | Switches the session to **Similarity Radio** anchored to the current track. |
| **`🎲`** | **Random Genre** | Spins the wheel and switches to a surprise genre or subgenre playlist. |
| **`📻`** | **Autoplay** *(Server Pro)* | Automatically posts (and streams in Voice) the next track as soon as the current song finishes. |

---

## Voice Channel Streaming (`/vplay` & `/voice`)

Want the bot to join your voice channel and play for everyone in the room?

1. Join any voice channel in your Discord server.
2. Run **`/vplay`** (leave `query` blank to stream the current Song Card in chat, or type any song, genre, or supported track URL like `/vplay query: house`).
3. Control playback anytime with **`/voice`**:
   - `🔊 Join Voice Channel` — Connect to your voice channel
   - `⏸️ Pause Playback` — Pause the current stream
   - `▶️ Resume Playback` — Resume where you left off
   - `⏭️ Skip / Next Track` — Skip to the next song in the session
   - `📜 Queue / Now Playing` — View the current track and upcoming session queue
   - `⏹️ Stop Playback` / `👋 Leave Voice Channel` — Stop audio or disconnect

---

## Slash Commands at a Glance

| Command | Example | Description |
| :--- | :--- | :--- |
| **`/play [query]`** | `/play query: lofi hip hop` | Play Top Hits (if blank), a genre, `random`, `<Song> by <Artist>`, or a supported song URL |
| **`/playlist <url> [shuffle] [loop]`** | `/playlist url: <playlist-url>` | Load and play a supported music playlist URL |
| **`/artist <name>`** | `/artist name: The Weeknd` | Play top studio tracks by a specific artist |
| **`/similar <song> [artist]`** | `/similar song: Starboy` | Play tracks similar to a song (Similarity Radio) |
| **`/autoplay [state] [genre]`** | `/autoplay state: On genre: rock` | Toggle hands-free song-length Autoplay On or Off *(Server Pro)* |
| **`/vplay [query]`** | `/vplay query: synthwave` | Join your voice channel and immediately stream audio *(Server Pro)* |
| **`/voice <action>`** | `/voice action: ⏭️ Skip` | All-in-one voice & playback control menu *(Server Pro)* |
| **`/clear`** | `/clear` | Clear the channel's recently played history for a fresh start |
| **`/help`** | `/help` | Show the private quick-reference command menu inside Discord |

---

## Server Pro & Pricing

**Music DJ Bot's core discovery is 100% Free Forever**—including `/play`, `/playlist`, `/artist`, `/similar`, inline Song Cards, `⏭️ Next`, `👍 Like`, and `🎲 Random`.

To cover dedicated server compute and persistent voice hosting, **Hands-Free Autoplay (`📻`)** and **High-Priority Voice Channel Streaming (`/vplay` & `/voice`)** are **Server Pro** features—unlocked for your **entire Discord server** with a **single one-time payment** (no monthly subscriptions).

| Plan | Price | What's Included |
| :--- | :---: | :--- |
| **Free Tier** | **$0 Forever** | Unlimited `/play`, `/playlist`, `/artist`, `/similar`, inline Song Cards, `⏭️ Next`, `👍 Like`, and `🎲 Random` |
| **Server Pro (Crypto — 20% Off)** | **$4 One-Time** | Unlocks **High-Priority Voice Channel Streaming (`/vplay` & `/voice`)** + **Hands-Free Autoplay (`📻`)** for your entire Discord server |
| **Server Pro (Card / Apple Pay)** | **$5 One-Time** | Unlocks **High-Priority Voice Channel Streaming (`/vplay` & `/voice`)** + **Hands-Free Autoplay (`📻`)** for your entire Discord server |

- **Unlock with Crypto ($4):** [https://coinos.io/musicdjbot](https://coinos.io/musicdjbot)
- **Unlock with Card / Apple Pay ($5):** [https://ko-fi.com/musicdjbot](https://ko-fi.com/musicdjbot)

> **How to Activate Server Pro:**
> Include your Discord **Server ID** in the payment note.
> *(Tip: Click `📻` or run `/vplay` inside your Discord server before upgrading and the bot will privately display your exact Server ID so you can copy and paste it.)*
