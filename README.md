# My iOS Shortcuts

> Just some shortcuts for iOS I wanted to share.

Thanks for checking out my first attempt at shortcuts for iOS! So far, I have a few that I’ve made. The first two I'm sharing I made for when I drive for Uber. When I accept a new passenger I always find myself doing the same tasks so I set these up to automate the process. The music one I made to make a QR code for songs in apple music, for sharing with friends and for my DayOne journal, hopefully, DayOne shortcuts coming soon!

## Installation

You can download this repo to [Working Copy][bf01a08f] and open the binary file using the sharing option (I find the best luck from the Files app) or click/copy the iCloud URL to open in Shortcuts.app and save to your device. I've added `.toml` files, where available, which can be used with [python-shortcuts][40d65457] in case you want to customize, edit or borrow snippets for use in a text editor and compile them yourself!

## Shortcuts:

### Signing Online - Uber

**Siri command:** "Hey Siri, I have a passenger"  
**What it does:** Plays Duran Duran Radio, Toggles DND on, sets display brightness to a generally tolerable level (except in bright sunlight), sets system volume to high and launches the Uber Driver app in case you had a different application open. I updated the shortcut to toggle WiFi off because when connecting to an open network, (say the phone connects to a Starbucks when at a light) trips may fail to accept while your phone may not have disconnected from the network yet and lose the ride.

[⬇️ Download](https://www.icloud.com/shortcuts/7b73a63bd55f4cc388b97988df6a3c32)

### Signing Offline - Uber

**Siri command:** "Hey Siri, no more passengers"  
**What it does:** Plays podcasts, toggles DND off and opens Waze, my preferred navigation app.

[⬇️ Download](https://www.icloud.com/shortcuts/681d4903541f47779b11a6c23efaaea8)

_Note: ~~Shortcuts doesn’t currently have a glyph for Uber so I used the Pied Piper symbol cuz it makes me chuckle and I love the show Silicon Valley~~ Sadly Apple seems to have removed the icons of popular brands 😢_

## Backup Shortcuts

### Zip to iCloud or Dropbox

Gets all your shortcuts & creates an archive with the title `Backups-<date>.zip` and saves them in either iCloud or Dropbox. Especially handy for quickly transferring to your computer so mess with python-shortcuts and Shortcuts JS with!

[Zip-to-Dropbox ⬇️ Download](https://www.icloud.com/shortcuts/431323d7a134482da00df878717c9005)
[Zip-to-iCloud ⬇️ Download](https://www.icloud.com/shortcuts/193b9be0bea84daaaa7686ad78b95bac)

## Music Shortcuts

### Armin Only

**What it does:** Offers a menu to play studio albums by the legend himself, Armin Van Buuren! Also includes a few Universal Religion compilations. All links are to Apple Music for now. This was an easy shortcut to get some practice with the `toml` format 😉. A much larger one coming soon offering options of every ASOT mix compilation! Stay tuned!

[⬇️ Download](https://www.icloud.com/shortcuts/e40a76c8852747269a7e1d782c95d695)

### Generate QR Code for Currently Playing Track 🎧

**What it does:** What the title says. I started with the apple shortcut to get the URL for a playing track and worked with it to create a QR code for easy sharing and to add to my journals in DayOne.

[⬇️ Download](https://www.icloud.com/shortcuts/a90c54c2dd6747efa30217363e586b59)

## Misc Shortcuts

### Crack is Whack

**What it does:** Summons Whitney from today view to remind people that crack is whack!

[⬇️ Download](https://www.icloud.com/shortcuts/d14046f886494633a0f7204850626e7e)

---

## Contributing

Feel free to use these shortcuts and customize to your own preferences! And if you have any cool ideas or recommendations don't hesitate to let me know!

---

## Useful Links

### Creating shortcuts

- [Shortcuts JS][513d0b26]
- [Python-Shortcuts][40d65457]
  - [Pythonista 3][c040d3d5] - Use Python on iOS!
  - [Pythonista 3 on the App Store](https://itunes.apple.com/us/app/pythonista-3/id1085978097?mt=8)

### Shortcuts Community

- [r/Shortcuts][5edb4a33]
  - [r/Shortcuts:wiki][c9413eef]
- [PowitOfficial/sirishortcuts][7cbfe5b2]
- [afrex/iOS-shortcuts][70653e8e]
- [jordanmerrick/shortcutsdirectory][014c8c40]
- [joshhighet/SiriShortcuts][de6c8f26]

[513d0b26]: https://shortcuts.fun "Shortcuts JS"
[40d65457]: https://pypi.org/project/python-shortcuts/ "Python-Shortcuts"
[c040d3d5]: http://omz-software.com/pythonista/ "Pythonista 3"
[5edb4a33]: https://www.reddit.com/r/shortcuts/?st=JQ5QCF4J&sh=3ce77f3a "r/Shortcuts"
[c9413eef]: https://www.reddit.com/r/shortcuts/wiki/index?st=JQ5QEB1V&sh=a51658ee "r/Shortcuts:wiki"
[7cbfe5b2]: https://github.com/PowitOfficial/sirishortcuts "PowitOfficial/sirishortcuts"
[70653e8e]: https://github.com/afrex/iOS-shortcuts "afrex/iOS-shortcuts"
[014c8c40]: https://github.com/jordanmerrick/shortcutsdirectory "jordanmerrick/shortcutsdirectory"
[de6c8f26]: https://github.com/joshhighet/SiriShortcuts "joshhighet/SiriShortcuts"
[bf01a08f]: https://itunes.apple.com/us/app/working-copy/id896694807?mt=8 "Working Copy on the App Store!"
