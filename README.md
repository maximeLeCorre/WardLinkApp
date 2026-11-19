# Wardlink

Play League of Legends from the couch, the kitchen or your wrist: Wardlink lets your phone and your watch drive
the League client running on your PC.

## What it does

The **Wardlink apps** (Android, iPhone, Wear OS, Apple Watch) show what your client is doing and act on it:

- **Start a game away from the desk**: launch League, pick a mode, make a lobby, invite friends, choose your
  positions, start the queue and see the waiting time.
- **Never miss a ready check**: the match found alert rings and vibrates on the phone and the watch, with
  *Accept* / *Decline* right in the notification, even when the app is closed.
- **Champion select**: pick or ban, swap with the ARAM bench, reroll, choose your summoner spells and rune page,
  and chat with your team.
- **Friends and chat**: who is online and in game, invitations to join, private messages with replies from the
  notification, friend requests, spectate a friend's game.
- **In game and after**: kills, deaths and assists live on the watch (with a sound and a vibration for each kill),
  then the end of game screen, honor and *Play again*.
- **Your history, kept**: the League client only remembers your last 20 games; Wardlink keeps every one on your
  PC, with statistics by mode and champion, and your games together with the friends you follow.
- **The rest of your account**: profile, ranks, collection, loot (open chests, upgrade or disenchant shards),
  missions and rewards to claim, Clash.

## How it works

**Wardlink.exe** (this download) is the small program that runs on the PC, as an icon near the clock. It contains
no game logic: it passes the apps' requests to the League client and keeps your game history. Everything else
lives in the apps.

- **Home network only.** The phone reaches the PC on your Wi-Fi; Wardlink refuses connections from outside it.
- **You pair by scanning the PC's screen.** In the Wardlink window, Devices › Show the QR code, and scan it with
  the phone app: the code works once, for 2 minutes. A watch takes its phone's pairing. You can unpair a device
  from either side at any time.
- **Only what the apps need.** A paired device reaches the parts of the client the apps use, nothing else:
  no sign-in data, no purchases, no settings.
- **Private.** Encrypted connections, no account to create, nothing collected about you. Only the iPhone's
  notifications while its app is closed go through our notification server, encrypted end to end: it cannot read
  them.

The apps are in testing for now (by invitation).

## Download

**Latest: [Wardlink 1.1.0](https://github.com/maximeLeCorre/WardLinkApp/releases/tag/v1.1.0)** — `Wardlink.exe`

Wardlink tells you itself when a newer version is out (its window links here).

## Check your copy

Only download it from this page. Before running it, check that its SHA-256 is the one listed below, in PowerShell:

```powershell
Get-FileHash .\Wardlink.exe -Algorithm SHA256
```

The exe is not code-signed yet: Windows SmartScreen may warn about an unknown publisher. A different hash means the
file is not ours: delete it.

## SHA-256 of every version

| Version | SHA-256 of `Wardlink.exe` |
|---|---|
| 1.1.0 | `17098d519617f73a862f29af7d6772f3616fa607fa317fedb00584cc7ae1ff5d` |
| 1.0.1 | `2cd6fc19099c0465d2b20295371346647f32dca68dff46608897ac3d52de659f` |
| 1.0.0 | `1302addf31890016d6bdf1893374e68e6c28bba5639551821ee5f255f0e1e3e4` |
| 0.6.0 | `f9741a484d9f1fd112b57f8980460b2bd9320fb51447b6169406a88949ba3b3f` |

---

Wardlink isn’t endorsed by Riot Games and doesn’t reflect the views or opinions of Riot Games or anyone officially
involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or
registered trademarks of Riot Games, Inc.
