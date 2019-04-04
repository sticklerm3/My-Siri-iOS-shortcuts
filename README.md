# My iOS Shortcuts

> Just some shortcuts for iOS I wanted to share.

Thanks for checking out my first attempt at shortcuts and GitHub! So far, I have a few that I’ve made. The first two I'm sharing I made for when I drive for Uber. When I accept a new passenger I always find myself doing the same tasks so I set these up to automate the process. The music one I made to make a QR code for songs in apple music, for sharing with friends and for my DayOne journal, hopefully, DayOne shortcuts coming soon!

## Installation

You can download this repo to [Working Copy](https://itunes.apple.com/us/app/working-copy/id896694807?mt=8) and open the binary file using the sharing option (I find the best luck from the Files app) or click/copy the iCloud URL to open in Shortcuts.app and save to your device. I've added `.toml` files, where available, which can be used with [python-shortcuts](https://pypi.org/project/python-shortcuts) in case you want to customize, edit or borrow snippets for use in a text editor and compile them yourself!

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

### 🎶 Generate QR Code for Currently Playing Track 🎧

**What it does:** What the title says. I started with the apple shortcut to get the URL for a playing track and worked with it to create a QR code for easy sharing and to add to my journals in DayOne.

[⬇️ Download](https://www.icloud.com/shortcuts/a90c54c2dd6747efa30217363e586b59)

## Misc Shortcuts

### Crack is Whack

**What it does:** Summons Whitney from today view to remind people that crack is whack!

[⬇️ Download](https://www.icloud.com/shortcuts/d14046f886494633a0f7204850626e7e)

---

## _in-progress_

### README-Gen

**What it does:** Prompts you for input to generate a basic `README.md` file for your project! It's pretty basic for now and will work on setting more customizations and support for initializing into WorkingCopy.

[⬇️ Download](https://www.icloud.com/shortcuts/25966278e7ca498f8bb75b19b16cc715)

#### to-do

- create prompt for username, email, & Twitter & GitHub username and repo for contributing section
- license selector
- create prompt for where to save readme
  - current options available in shortcuts re Dropbox & iCloud
  - look into a version to add to WorkingCopy app

### DayOne entry of currently listening

Studying existing shortcuts & experimenting with app integrations to make my entry in one click, instead of 3... Cuz, you know, we gotta turn it up to 11 🎚!

---

## Contributing

Feel free to use these shortcuts and customize to your own preferences! And if you have any cool ideas or recommendations don't hesitate to let me know!

---

## Useful Links

### Creating shortcuts

- [Shortcuts JS](https://shortcuts.fun)
- [Python-Shortcuts](https://pypi.org/project/python-shortcuts/)
- [Pythonista 3](http://omz-software.com/pythonista/)
  - [Pythonista 3 on the App Store](https://itunes.apple.com/us/app/pythonista-3/id1085978097?mt=8)

### Shortcuts Community

- [r/Shortcuts](https://www.reddit.com/r/shortcuts/?st=JQ5QCF4J&sh=3ce77f3a)
  - [r/Shortcuts:wiki](https://www.reddit.com/r/shortcuts/wiki/index?st=JQ5QEB1V&sh=a51658ee)
- [PowitOfficial/sirishortcuts](https://github.com/PowitOfficial/sirishortcuts)
- [afrex/iOS-shortcuts](https://github.com/afrex/iOS-shortcuts)
- [jordanmerrick/shortcutsdirectory](https://github.com/jordanmerrick/shortcutsdirectory)
- [joshhighet/SiriShortcuts](https://github.com/joshhighet/SiriShortcuts)
