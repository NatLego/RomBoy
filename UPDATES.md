# Development updates

[Back to RomBoy](README.md)

## 29 September 2026 · Coming in the next release

RomBoy’s next update brings a refreshed Home screen, easier cover artwork management and dedicated AYN Thor support.

- **Everything together on Home:** access My games, Get games, Connect, Settings and Skins from clearly labelled, colourful boxes.
- **A consistent look:** matching icons, fonts and controls throughout the app, with the updated library design.
- **Find and change game covers:** search for artwork online or choose your own image using a clearly labelled button. Supports locally added games and RomM games, with custom covers saved on your device.

### Built for AYN Thor

RomBoy is being adapted for Thor’s built-in controls and dual screens. Browse your library on the lower screen while viewing the selected game above, with dedicated layouts for getting games, managing connections and changing settings.

Single-screen games play on the top display by default, with gameplay controls on the lower screen and the option to switch screens. You can also open another app on the lower display while keeping your game above.

Both screens share RomBoy’s landscape startup animation.

These features are in development for the next release and are not yet available in production.

## 29 September 2026 · Production pending

RomBoy has passed closed testing, and beta testing is now closed. The production release is pending.

## 24 September 2026 · Mega Drive testing continues

The original Mega Drive / Genesis core is still experimental and isn't available in the Google Play app.

Work on the separate development build has focused on CPU performance, automated checks for regressions and testing games. A revised display path passed a six-minute gameplay check and selected shorter checks on one test phone, with no recorded audio underruns in those runs. Further CPU work passed an opening check that previously failed and a one-minute combat check, both with no recorded audio underruns. The regression checks found no changes to execution state, sound samples or pixels. Other scenes still have intermittent audio failures. Graphics issues and wider game compatibility need more testing and fixes.

Next are fixes for those failures and more gameplay and controller checks. These results don't establish broad compatibility. There is no release date.

## 24 September 2026 · Help links, sharing and feedback

Version 0.1.0-testing.6 was submitted to the Alpha closed-testing track. It was awaiting Google Play approval when this update was posted.

- Settings → Help now includes the existing [privacy policy](https://letmehelp-romboy.web.app/privacy-policy/) and this GitHub community page.
- Share RomBoy and Rate RomBoy are on the main Settings page. Share opens Android’s sharing options; Rate opens RomBoy’s Google Play listing.
- The store title and descriptions were also submitted for review, under RomBoy: Retro Game Emulator.

These changes were checked on a Pixel in portrait and landscape before submission. Current console support remains GB, GBC and GBA. This update does not add a new core or change gameplay controls.

Use [Discussions](https://github.com/NatLego/RomBoy/discussions) for questions and conversation, or [Issues](https://github.com/NatLego/RomBoy/issues) for bug reports and feature requests.

## 17 September 2026 · Consistent controls and larger game view

Version 0.1.0-testing.5 became available to closed testers. Touch controls now use the same sizing in portrait and landscape. Screenshot and menu buttons sit in side panels to leave more room for the game. The display still expands when a controller is connected.

## 14 September 2026 · Beta testing

Beta sign-up opened for free internal testing through Google Play, with up to 100 places including existing testers. The sign-up page explained that places would be allocated in order and installation invitations emailed separately.

## 14 September 2026 · Introducing RomBoy

The RomBoy GitHub page launched with app information, eight phone mock-ups, setup instructions and a roadmap.

At the time, the development build included GB, GBC and GBA emulation, local imports, optional RomM connection, offline play, supported server save backups, customisable skins and compatible controller support.

Preparation for Google Play testing was underway.

The roadmap covered development of RomBoy's own Mega Drive / Genesis core, planned Nintendo DS support, and exploration of remote two-player play. Other cores were also being considered. Remote multiplayer may not be released. See the [roadmap](ROADMAP.md) for current plans.

Use the [issue tracker](https://github.com/NatLego/RomBoy/issues) for feedback. Updates here cover app changes, testing and releases.


