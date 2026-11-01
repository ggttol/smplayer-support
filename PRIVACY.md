# Privacy Policy / 隐私政策

[English](#english) · [简体中文](#简体中文)

_Last updated / 最后更新：2026-11-01_

## English

SMPlayer is a music player for the music you already own. It has no accounts of its own, no analytics, no ads and no tracking, and the developer does not collect any of your data.

**What stays on your devices**
- Your music sources: server addresses and user names are saved on the device, and passwords are saved in the Keychain.
- Your library cache, playlists, settings, downloaded songs, lyrics and listening history are stored on the device.
- If iCloud is turned on, your music sources (with passwords in iCloud Keychain) and settings sync between your own devices through your iCloud account. The developer cannot read this data.
- None of this is sent to the developer.

**Network connections SMPlayer makes**
- **Your own servers.** SMPlayer connects directly to the servers you add: Subsonic / Navidrome / SMPlayer Server, Jellyfin / Emby, Plex, Synology Audio Station, WebDAV and SMB. This is how it browses and plays your music.
- **Plex sign-in.** If you sign in with a Plex account, SMPlayer talks to plex.tv to sign you in and to find your Plex servers.
- **Synology QuickConnect.** If you enter a QuickConnect ID, SMPlayer sends it to Synology's QuickConnect service to look up your NAS address.
- **Online lyrics.** When a song has no synced lyrics on your device or server, SMPlayer sends the song's title, artist, album and duration to [LRCLIB](https://lrclib.net), and the title, artist and duration to the public lyrics search of NetEase Cloud Music, QQ Music and Kugou. No account or device identifier is sent. You can turn this off in **Settings › Lyrics**.
- **ListenBrainz (optional).** Only if you enter your own ListenBrainz token, SMPlayer submits the songs you play to [ListenBrainz](https://listenbrainz.org) under your account.
- **Local network.** SMPlayer uses Bonjour and SSDP to find music servers and speakers (UPnP / DLNA) on your local network. When you cast to a speaker, the speaker streams the song from your server directly.

These requests go straight from your device to the services above. Their own privacy policies apply.

**Purchases.** In-app purchases are handled by Apple. The developer receives no payment details.

**Contact.** Please open an issue at https://github.com/ggttol/smplayer-support/issues.

## 简体中文

SMPlayer 是一款播放你自己音乐的播放器。它没有自己的账号系统，也没有统计、广告或追踪，开发者不收集你的任何数据。

**留在你设备上的数据**
- 你添加的音乐源：服务器地址和用户名保存在设备上，密码保存在钥匙串里。
- 曲库缓存、歌单、设置、下载的歌曲、歌词和听歌记录都保存在设备上。
- 打开 iCloud 时，音乐源（密码存在 iCloud 钥匙串）和设置会通过你的 iCloud 账号在你自己的设备之间同步，开发者无法读取。
- 这些数据都不会发给开发者。

**SMPlayer 会发起的网络连接**
- **你自己的服务器**：SMPlayer 直接连接你添加的服务器，包括 Subsonic / Navidrome / SMPlayer 服务器、Jellyfin / Emby、Plex、群晖 Audio Station、WebDAV 和 SMB，用来浏览和播放你的音乐。
- **Plex 登录**：用 Plex 账号登录时，SMPlayer 会连接 plex.tv 完成登录并查找你的 Plex 服务器。
- **群晖 QuickConnect**：填写 QuickConnect ID 时，SMPlayer 会把它发给群晖的 QuickConnect 服务，用来查询你的 NAS 地址。
- **在线歌词**：设备和服务器上都没有带时间轴的歌词时，SMPlayer 会把歌名、歌手、专辑和时长发给 [LRCLIB](https://lrclib.net)，把歌名、歌手和时长发给网易云音乐、QQ 音乐、酷狗的公开歌词搜索。不发送任何账号或设备标识。可以在“设置 › 歌词”里关闭。
- **ListenBrainz（可选）**：只有在你填写了自己的 ListenBrainz 令牌时，SMPlayer 才会把你播放的歌曲提交到你在 [ListenBrainz](https://listenbrainz.org) 的账号。
- **局域网**：SMPlayer 通过 Bonjour 和 SSDP 发现局域网里的音乐服务器和音箱（UPnP / DLNA）。投放到音箱时，由音箱直接从你的服务器拉取歌曲。

这些请求都从你的设备直接发给上面的服务，适用它们各自的隐私政策。

**购买**：App 内购买由 Apple 处理，开发者拿不到任何付款信息。

**联系方式**：请在 https://github.com/ggttol/smplayer-support/issues 提交 Issue。
