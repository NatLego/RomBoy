# RomBoy roadmap

[Back to RomBoy](README.md)

RomBoy currently supports Game Boy, Game Boy Color and Game Boy Advance. An original Mega Drive core is in development, and Nintendo DS support is planned.

Updated 29 September 2026. There are no release dates for the features below. Plans may change as testing continues.

## What's next

| Area | Status | Aim |
| --- | --- | --- |
| Android launch | Production pending | Release RomBoy with GB, GBC and GBA support. |
| Original Mega Drive core | In development | Build RomBoy's own Sega Mega Drive / Genesis emulator. |
| AYN Thor | In development | Use the built-in controls, show game artwork on the second screen and let players swap the screens. |
| Nintendo DS | Planned | Support two game screens and touch controls, including separate displays on compatible handhelds. |
| Remote two-player play | Exploratory | Find out whether people in different locations can play supported games together. |
| Additional cores | Under consideration | Add more systems that work well on Android. |

## Android app

The app supports local imports and downloads from a compatible RomM server. Games stored on your phone work offline. It also includes saves, supported server backups and restores, customisable skins, dark mode and compatible controller support.

Status: Production pending.

See [Development updates](UPDATES.md) for recent changes.

## Original Mega Drive core

Status: In development.

RomBoy's developer is building an original Sega Mega Drive / Genesis emulator. The work covers the console's CPU, graphics and sound, along with testing how games run.

The aim is to play Mega Drive games through RomBoy's existing library. Before release, the core needs checks for game compatibility, timing, sound, performance and saves.

Testing uses a separate development build. A revised display path passed a six-minute gameplay check and selected shorter checks on one phone, with no recorded audio underruns. Further CPU work passed an opening check that had previously failed and a one-minute combat check, also without recorded audio underruns.

Other scenes still have intermittent audio failures. Graphics problems and wider game compatibility need more work. These checks don't establish that the core is ready for release.

The core isn't available in the public app. There is no release date or promised compatibility list.

## AYN Thor

Status: In development.

Work has started on a handheld layout for AYN Thor. The aim is to play on the top screen by default and show the current game's cover on the other screen, with a button to swap the screens and a remembered screen preference. The game view uses the available screen area while keeping its original proportions, with the RomBoy button within reach at the bottom right.

This is development work and is not in the released app. Gameplay and physical control checks are still needed.

## Nintendo DS

Status: Planned.

DS support needs a usable layout for two screens, touch input and physical controls, as well as working emulation and game compatibility. On compatible dual-screen handhelds such as AYN Thor, the aim is to put each DS screen on a separate physical display.

It isn't in the current app. Details will be added as development progresses.

## Remote two-player play

Status: Exploratory.

The idea is to let two people in different locations play supported games together. First, we need to find out which systems and games could work, how players would connect, and whether the game would stay responsive and in sync over the internet. Slow connections and dropped connections would need testing too.

This may be limited to selected games or systems, or may not be released. There is no release date.

## Other systems

Status: Under consideration.

Other cores will depend on game compatibility, Android performance, controls and reliable saves. They also need to be maintainable and suitable for distribution.

No other systems are confirmed. If you'd like to suggest one, tell us which games you want to play and what you'd like RomBoy to do.

## Updates and feedback

[Development updates](UPDATES.md) records progress, testing opportunities and releases. This roadmap is updated when the plans change.

In development means work is underway. Planned means we intend to add it. Exploratory means we're checking whether it can work. Under consideration means it hasn't been chosen for development.

[Suggest a feature](https://github.com/NatLego/RomBoy/issues/new?template=feature_request.yml) or visit the [issue tracker](https://github.com/NatLego/RomBoy/issues).



