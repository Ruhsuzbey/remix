# 🎵 Remix

An operational and exprimental Telegram music bot.

---

## 🎖 <a id="achievements"></a>Achievements

- [Mentioned in Awesome grammY](https://github.com/grammyjs/awesome-grammY)
- [Mentioned in Awesome tgcalls](https://github.com/tgcalls/awesome-tgcalls)

## ✨ <a id="features"></a>Features

### 😉 Streams Whatever You Like

You can stream audio files, voice messages, YouTube videos with any duration,
YouTube lives, YouTube playlists and even custom inputs like radios or files in
the place it is hosted!

### 📊 Streams in Multiple Places at Once

Allows you to stream different things in multiple chats simultaneously. Each
chat will have its own song queue.

### ⚡️ Fast & Light

Starts streaming your inputs while downloading and converting them. Also, it
doesn't make produce files.

### 😎 Has a Lot of Controls

Lets you adjust volume, loop, pause, resume, mute, unmute. Also, it has a
control panel.

### 👮🏻‍♀️ Safe

Restricts control and sensitive commands to admins.

### 🗣 Speaks Different Languages

Remix is multilingual and speaks [various languages](#available-languages),
thanks to the translators.

### 🗑 Clean

Its responses and source code don't say anything referring to Calls Music.
Except some places like [`package.json`](./package.json).

## 🚀 <a id="running"></a>Running

1. Copy `example.env` to `.env` and fill it with your credentials.
2. Install dependencies and build:

```bash
npm install && npm run build
```

3. Start:

```bash
npm start
```

## ☁️ <a id="cloud"></a>Cloud platforms

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Ruhsuzbey/remix)

## ⚒ <a id="configuring"></a>Configuring

- `BOT_TOKEN`: Telegram bot token.
- `STRING_SESSION`: A GramJS/Telethon string session. You can generate one
  [here](https://ssg.roj.im).
- `API_ID`: Telegram app ID.
- `API_HASH`: Telegram app hash.
- `LOCALE`: An [available](#available-languages) bot language. Default: `en`.
- `MAX_PLAYLIST_SIZE`: Max YouTube playlist size. Default: `10`.
- `COOKIES`: Cookies for YouTube requests. Default: none.

## 📄 <a id="commands"></a>Commands

### 🎶 stream

#### _Aliases: s, play, p_

Takes a custom input, audio file, voice message or YouTube video/playlist
link/ID and streams/queues it.

Custom inputs should be passed like this:

```text
/stream custom <your_custom_input>
```

> You can replace `<your_custom_input>` with a valid Ffmpeg input, for example:
> URL to a media file with audio, or a radio stream.

### 🔍 search

#### _Aliases: find_

Searches for a YouTube video.

### ✅ cancel

Cancels the active YouTube video search.

### 🔢 playlist

#### _Aliases: pl, list_

Streams a YouTube playlist.

### 🎵 now

#### _Aliases: ns, cs, np, cp_

Displays the currently streamed item.

### 📝 lyrics

#### _Aliases: ly_

Sends the lyrics of the currently streamed item.

### 🎛 panel [👮🏻‍♀️]

#### _Aliases: menu, control, controls_

Opens the controls panel.

### 🔁 loop [👮🏻‍♀️]

#### _Aliases: repeat_

Toggles loop.

### 🔀 shuffle [👮🏻‍♀️]

#### _Aliases: sh, mix_

Shuffles the items in the queue.

### 🔉 volume [👮🏻‍♀️]

#### _Aliases: vol, v_

Sets the volume.

### ⏸ pause [👮🏻‍♀️]

Pauses the stream.

### ▶️ resume [👮🏻‍♀️]

#### _Aliases: re, res, continue_

Resumes the stream.

### 🔇 mute [👮🏻‍♀️]

#### _Aliases: m_

Mutes the stream.

### 🔈 unmute [👮🏻‍♀️]

#### _Aliases: um_

Unmutes the stream.

### ⏩ skip [👮🏻‍♀️]

#### _Aliases: next_

Skips the current item.

### ⏹ leave [👮🏻‍♀️]

#### _Aliases: stop_

Clears the queue and stops streaming.

### 🗑 cache [👮🏻‍♀️]

Deletes caches.

## 🗣 <a id="available-languages"></a>Available languages

```text
bn    Bengali
ckb   Central Kurdish
de    German
en    English
es    Spanish
fa    Farsi
id    Indonesian
ml    Malayalam
pt_BR Brazilian Portuguese
si    Sinhalese
tr    Turkish
```

## 🛫 <a id="support"></a>Support

Join [our chats](https://callsmusic.me).

## 💜 <a id="contributing"></a>Contributing

New languages, bug fixes and improvements following
[our contribution guidelines](./CONTRIBUTING.md) are warmly welcomed!

## 📃 <a id="license"></a>License

Remix is licenced under the GNU Affero General Public License v3.0. Read more
[here](./LICENSE).
