# Development updates

[Back to RomBoy](README.md)

## 24 September 2026 · Mega Drive testing continues

**The original Mega Drive / Genesis core remains experimental and is not available in the Google Play app.**

Work in a separate development build includes CPU performance improvements, automated regression checks and real-game testing. A revised display path has now passed a six-minute gameplay check and selected shorter checks on one test phone, with no recorded audio underruns in those runs. Further CPU work has now passed an opening check that previously failed and a one-minute combat check, both with no recorded audio underruns. Regression comparisons also preserved execution state, sound samples and pixels. Intermittent audio failures in other scenes, graphics issues and broader compatibility still need testing and fixes.

The next work is to resolve those failures and complete further gameplay and controller checks. This is a development update, not a core release or a compatibility announcement; there is no announced release date.

## 24 September 2026 · Help links, sharing and feedback

**0.1.0-testing.6 has been submitted for Closed testing - Alpha. Google Play approval is pending; this is not a production release.**

- Settings → Help now includes the existing [privacy policy](https://letmehelp-romboy.web.app/privacy-policy/) and this GitHub community page.
- Share RomBoy and Rate RomBoy are on the main Settings page. Share opens Android’s sharing options; Rate opens RomBoy’s Google Play listing.
- The store title and descriptions have also been submitted for review, under **RomBoy: Retro Game Emulator**.

These changes were checked on a Pixel in portrait and landscape before submission. Current console support remains GB, GBC and GBA. This update does not add a new core or change gameplay controls.

Use [Discussions](https://github.com/NatLego/RomBoy/discussions) for questions and conversation, or [Issues](https://github.com/NatLego/RomBoy/issues) for bug reports and feature requests.

## 17 September 2026 · Consistent controls and larger game view

**0.1.0-testing.5 became available to closed testers.** Portrait and landscape use consistent touch-control sizing. Screenshot and menu controls occupy side panels to preserve game space, with controller display behaviour retained.

## 14 September 2026 · Beta sign-up opens

[Request a place in the RomBoy beta](https://docs.google.com/forms/d/e/1FAIpQLSdVWGCNsiKHqh1iCb71eR9xDIjbLoFTNzuqHjNhJQYprzpiQw/viewform). Available places are allocated first come, first served within Google Play's maximum of 100 internal testers, including existing testers. Internal testers can install the beta free through Google Play.

Signing up requests a place. Installation invitations are sent by email once a tester is added. If the test is full, we will contact people in sign-up order as places become available.

## 14 September 2026 · Introducing RomBoy

RomBoy's public showcase brings together the current app features, eight phone mock-ups, setup guidance and the roadmap.

The current development build includes GB, GBC and GBA emulation, local imports, optional RomM connection, offline play, supported server save backups, customisable skins and compatible controller support.

Google Play release preparation is underway. A public download or testing link will be added when available.

The roadmap includes development of RomBoy's own Mega Drive / Genesis core, planned Nintendo DS support, and exploration of remote two-player play. Additional cores are being considered. Remote multiplayer is an investigation, with no guaranteed release. The [roadmap](ROADMAP.md) separates active work from plans and possibilities.

Use the [issue tracker](https://github.com/NatLego/RomBoy/issues) for feedback. Future notes here will describe changes, testing opportunities and release progress.
