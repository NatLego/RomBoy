# RomBoy roadmap

[Back to RomBoy](README.md)

RomBoy starts with Game Boy, Game Boy Color and Game Boy Advance. The next chapter includes an original Mega Drive core, Nintendo DS support and research into playing together across a distance.

Updated **24 September 2026**. This is the development direction, not a release schedule. Features move into the app when they are ready; experimental work may change or may not reach release.

## Development at a glance

| Area | Status | Aim |
| --- | --- | --- |
| Android launch | **Closed testing** | Test and refine the GB, GBC and GBA experience before production release. |
| Original Mega Drive core | **In development** | Build RomBoy's own emulator core for Sega Mega Drive / Genesis. |
| Nintendo DS | **Planned** | Add DS play with a considered approach to its two screens and touch input. |
| Remote two-player play | **Exploratory** | Investigate whether two people can play supported games together from different locations. |
| Additional emulator cores | **Under consideration** | Expand the supported systems where they can work well within RomBoy. |

## The foundation: Android release

The current development build includes GB, GBC and GBA emulation, local imports, optional RomM connection, selected downloads and offline play. Saves, supported server backups and restores, customisable skins, dark mode and compatible controllers form part of that experience.

RomBoy is in closed testing on Google Play. The immediate focus is addressing tester feedback and preparing for production access. Version 0.1.0-testing.6 has been submitted for review with Help links and sharing and rating actions; see [Development updates](UPDATES.md) for release status. [Beta sign-up is open](https://docs.google.com/forms/d/e/1FAIpQLSdVWGCNsiKHqh1iCb71eR9xDIjbLoFTNzuqHjNhJQYprzpiQw/viewform), with limited places allocated first come, first served. Installation invitations are sent separately. Release news will appear on the [main page](README.md).

## An original Mega Drive core

**Status: In development**

RomBoy's developer is building an original Sega Mega Drive / Genesis emulator core. This is a substantial development project: reproducing the console's behaviour, bringing its graphics and audio together, and working through real-game compatibility.

The aim is to make Mega Drive play part of RomBoy's existing library and playing experience. Progress will be assessed through compatibility, timing, sound, performance and reliable handling of saves. Development updates will distinguish what has been demonstrated from what is still being worked on.

Testing is taking place in a separate development build. A revised display path passed a six-minute gameplay check and selected shorter checks on one test phone, with no recorded audio underruns in those runs. Further CPU work passed a previously failing opening check and a one-minute combat check without recorded audio underruns. Intermittent audio failures in other scenes, graphics issues and broader compatibility still need testing and fixes. These results do not establish broad game compatibility or release readiness.

There is no announced release date or promised compatibility list. The core is not available in the current public-facing feature set.

## Nintendo DS support

**Status: Planned**

Bring Nintendo DS games into RomBoy, with attention to how two screens, touch input and physical controls work on a phone. Screen layout and usability are part of the work, alongside emulation and compatibility.

DS support is not in the current build. Implementation details and availability will be shared as development progresses.

## Two players, different places

**Status: Exploratory — no guaranteed release**

Investigate remote two-player play so that two people in different locations could play supported games together through RomBoy.

The first step is establishing technical feasibility: which systems and games could support it, how the players would connect, and whether play can stay responsive and in sync over a real internet connection. Testing would also need to establish what happens when a connection slows or drops.

This is an intention to investigate and attempt the feature. It is not a promise of online multiplayer, support for every system, or a release date. The outcome may be a limited feature for selected games or systems, or a decision not to ship it.

## Future cores

**Status: Under consideration**

Other systems may follow. Candidates will be considered against game compatibility, performance on Android phones, controls, save reliability and whether the core can be responsibly maintained and distributed.

No additional systems are confirmed at this stage. Suggestions are welcome, particularly when they explain the games and playing experience people want from RomBoy.

## How progress will be shared

[Development updates](UPDATES.md) will record meaningful progress, testing opportunities and released features. Plans will be revised when testing or technical findings change what is practical.

**In development** means active work. **Planned** means an intended direction. **Exploratory** means feasibility is still being investigated. **Under consideration** means a possibility, with no commitment to build it.

[Suggest a feature](https://github.com/NatLego/RomBoy/issues/new?template=feature_request.yml) or follow the [issue tracker](https://github.com/NatLego/RomBoy/issues) for feedback and discussion.
