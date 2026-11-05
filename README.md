<div align="center">

<img src="logo.png" alt="Music DJ Bot Logo" width="160" />

# 🎧 Music DJ Bot for Discord

**Studio-quality music discovery, interactive Song Cards, and live 256kbps Voice Radio for your Discord server.**

[![Add to Discord](https://img.shields.io/badge/➕_Add_to_Your_Discord_Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1565796454037979226)
[![Support on Ko-fi](https://img.shields.io/badge/💳_Unlock_Server_Pro_($5)-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/musicdjbot)
[![Pay with Crypto](https://img.shields.io/badge/⚡_Unlock_with_Crypto_($4)-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)](https://coinos.io/musicdjbot)

</div>

---

## 🔥 Why Music DJ Bot?

Most Discord music bots force everyone into a voice channel just to hear a song, break constantly, or flood your chat with low-quality reuploads, gaming clips, and 3-hour mixes. **Music DJ Bot** is built differently:

- 🃏 **Play Directly in Text Chat — Or Stream Live in Voice**: Every track updates a clean, playable **Song Card** right in your channel so members can listen inline at their own pace *or* stream together in Voice.
- 📌 **Zero Chat Clutter (Single Card Mode by Default)**: By default, new songs update a single active Song Card in place (`/history off`), and all control/status commands reply privately (ephemerally) so your music channel stays spotless. Prefer a scrolling feed of every song played? Toggle `/history state: On` anytime!
- 🎛️ **One-Click DJ Deck**: Skip tracks (`⏭️`), build a similarity radio station (`👍`), spin the genre wheel (`🎲`), or toggle hands-free Autoplay (`📻`) with a single click—no typing required.
- 🧠 **Real Music Discovery**: Powered by multi-source music catalog intelligence. Discover top hits, deep subgenres, full artist catalogs, or songs that sound just like your favorite track.
- 🛡️ **100% Studio Music Guarantee**: Automatically blocks short-form clips (<65s), livestreams, gaming videos, vlogs, tutorials, reaction videos, AI-generated music spam, and anything over 15 minutes. Only real studio songs get through.
- 🔊 **Dedicated 256kbps Voice Streaming**: Crystal-clear 256kbps Opus voice channel playback with custom server volume (`/volume`) and automatic track progression.

---

## 🚀 Quickstart: How to Use It in 30 Seconds

Just type `/` in any Discord channel where the bot has access. Many commands include **instant autocomplete menus** so you don't even have to type!

### 1️⃣ Discover Top Hits or Any Genre (`/play`)
- **Top Hits**: Type `/play` and press **Enter** (leave `query` blank) to play today's trending music.
- **Pick a Genre**: Click `query` to choose from presets like `🎲 Random Genre`, `🔥 Top Hits`, `🎸 Rock`, `🪩 House`, `🎷 Jazz`, or type **any** genre or subgenre:
  - `/play query: synthwave`
  - `/play query: 90s hip hop`
  - `/play query: liquid drum and bass`

### 2️⃣ Play a Specific Song or Direct Track Link (`/play`)
- **By Song & Artist**:
  - `/play query: Harder Better Faster Stronger by Daft Punk`
  - `/play query: Kavinsky - Nightcall`
- **By Supported Music Link**:
  - Paste any supported song URL directly into `query`.
  - *(The bot automatically verifies that the link is a real studio song between 65 seconds and 15 minutes, then queues up similar tracks for your next skip!)*

### 3️⃣ Play an Artist's Best Tracks (`/artist`)
- `/artist name: Daft Punk`
- `/artist name: Fleetwood Mac`

### 4️⃣ Start a "Similar Songs" Radio Station (`/similar`)
Love a track's vibe and want more like it?
- `/similar song: Nightcall artist: Kavinsky`
- Or simply click the **`👍` (Like)** button under any Song Card in chat!

### 5️⃣ Load a Music Playlist (`/playlist`)
Bring your own public or unlisted music playlists into Discord with optional **Shuffle** and **Loop** modes:
- `/playlist url: <playlist-url> shuffle: True loop: False`

---

## 🎛️ Using the Interactive Song Card Buttons

Every song posted by Music DJ Bot comes with 4 interactive controls underneath the player:

| Button | Name | What It Does |
| :---: | :--- | :--- |
| **`⏭️`** | **Next Track** | Instantly skips to the next pre-loaded song in your current genre, playlist, artist, or similarity session. |
| **`👍`** | **Like / More Like This** | Tells the DJ you love this song and switches the session to **Similarity Radio** anchored to that track. |
| **`🎲`** | **Random Genre** | Spins the wheel and switches to a surprise genre or subgenre playlist. |
| **`📻`** | **Autoplay** *(Server Pro)* | Automatically posts (and streams in Voice) the next track as soon as the current song finishes. |

---

## 🔊 Voice Channel Streaming (`/vplay`, `/voice` & `/volume`)

Want the bot to join your voice channel and play for everyone in the room?

1. Join any voice channel in your Discord server.
2. Run **`/vplay`** (leave `query` blank to stream the current Song Card in chat, or type any song, genre, or supported track URL like `/vplay query: house`).
3. Adjust playback volume anytime with **`/volume level: 100`** (`0%–200%`, default `85%` — saved automatically for your server).
4. Control playback anytime with **`/voice`**:
   - `🔊 Join Voice Channel` — Connect to your voice channel
   - `⏸️ Pause Playback` — Pause the current stream
   - `▶️ Resume Playback` — Resume where you left off
   - `⏭️ Skip / Next Track` — Skip to the next song in the session
   - `📜 Queue / Now Playing` — View the current track and upcoming session queue (also available anytime via **`/queue`**)
   - `🎚️ Volume (View / Set)` — Check or change the server's voice playback volume
   - `⏹️ Stop Playback` / `👋 Leave Voice Channel` — Stop audio or disconnect

---

## 📋 All Slash Commands at a Glance

| Command | Example | Description |
| :--- | :--- | :--- |
| **`/play [query]`** | `/play query: lofi hip hop` | Play Top Hits (if blank), a genre, `random`, `<Song> by <Artist>`, or a supported song URL |
| **`/playlist <url> [shuffle] [loop]`** | `/playlist url: <playlist-url>` | Load and play a supported music playlist URL |
| **`/artist <name>`** | `/artist name: The Weeknd` | Play top studio tracks by a specific artist |
| **`/similar <song> [artist]`** | `/similar song: Starboy` | Play tracks similar to a song (Similarity Radio) |
| **`/queue`** | `/queue` | View the channel's Now Playing track and upcoming session queue |
| **`/autoplay [state] [genre]`** | `/autoplay state: On genre: rock` | Toggle hands-free song-length Autoplay On or Off *(Server Pro)* |
| **`/vplay [query]`** | `/vplay query: synthwave` | Join your voice channel and immediately stream 256kbps audio *(Server Pro)* |
| **`/voice <action> [volume]`** | `/voice action: ⏭️ Skip` | All-in-one voice & playback control menu *(Server Pro)* |
| **`/volume [level]`** | `/volume level: 90` | View or set voice channel volume from `0%` to `200%` (default `85%`) *(Server Pro)* |
| **`/history [state]`** | `/history state: Off` | Toggle Song Card history **Off** (Single Card Mode, default) or **On** (post new cards) |
| **`/clear`** | `/clear` | Clear the channel's recently played history for a fresh start |
| **`/help`** | `/help` | Show the private quick-reference command menu inside Discord |

---

## 💎 Server Pro (VIP Unlock) & Donations

**Music DJ Bot's core discovery is 100% Free Forever**—including `/play`, `/playlist`, `/artist`, `/similar`, `/queue`, `/history`, inline Song Cards, `⏭️ Next`, `👍 Like`, and `🎲 Random`.

To cover dedicated server compute and persistent voice hosting, **Hands-Free Autoplay (`📻`)** and **High-Priority Voice Channel Streaming (`/vplay`, `/voice` & `/volume`)** are **Server Pro** features—unlocked for your **entire Discord server** with a **single one-time payment** (no monthly subscriptions!).

| Plan | Price | What's Included |
| :--- | :---: | :--- |
| **Free Tier** | **$0 Forever** | Unlimited `/play`, `/playlist`, `/artist`, `/similar`, `/queue`, `/history`, inline Song Cards, `⏭️ Next`, `👍 Like`, and `🎲 Random` |
| **💎 Server Pro (Crypto — 20% Off)** | **$4 One-Time** | Unlocks **Hands-Free Autoplay (`📻`)** + **High-Priority 256kbps Voice Streaming (`/vplay`, `/voice` & `/volume`)** for your entire Discord server |
| **💎 Server Pro (Card / Apple Pay)** | **$5 One-Time** | Unlocks **Hands-Free Autoplay (`📻`)** + **High-Priority 256kbps Voice Streaming (`/vplay`, `/voice` & `/volume`)** for your entire Discord server |

### 🔗 Unlock Server Pro or Donate Today:
- ⚡ **Crypto ($4 — Discounted):** [https://coinos.io/musicdjbot](https://coinos.io/musicdjbot)
- 💳 **Card / Apple Pay ($5):** [https://ko-fi.com/musicdjbot](https://ko-fi.com/musicdjbot)

> **💡 How to Activate Server Pro:**
> Include your Discord **Server ID** in the payment note!
> *(Tip: If you click `📻` or run `/vplay` inside your Discord server before upgrading, the bot will automatically display your exact Server ID in a private message so you can copy and paste it!)*
