# My iOS Shortcuts

> Just some shortcuts for iOS I wanted to share.

Thanks for checking out my first attempt at shortcuts and github! Sofar, i have a few that ive made.  The first two im sharing I made for when i drive for Uber.  When I accept a new passenger i always find myself doig the same tasks so i set these up to automate the process. The music one I made to make a qr code for songs in apple music, for sharing with friends and for my DayOne journal, hopefully DayOne shortcuts coming soon!

## Shortcuts:

### Signing Online - Uber

**Siri command:** "Hey Siri, I have a passenger"
**What it does:**Plays Duran Duran Radio, Toggles DND on, sets display brightness to a generally tolerabble level (except in bright sunlight), sets system volume to high and launces the Uber Driver app in case you had a different application open. I updated the shortcut to toggle WiFi off because when connecting to an open network, (say the phone connects to a starbucks when at a light) trips may fail to accept while your phone may not have disconnected from the network yet and lose the ride. 

### Signing Offline - Uber

**Siri command:** "Hey Siri, no more passengers"
**What it does:** Plays podcasts, toggles DND off, and opens Waze, my preferred navigation app.

_Note: Shortcuts doesn't currently have a glyph for Uber so I used the Pied Piper symbol cuz it makes me chuckle and I love the show Silicon Valley 😊_

### Generate QR Code for Currently Playing Track

**What it does:** What the title says. I started with the apple shortcut to get the URL for a playing track and worked with it to create a QR code for easy sharing and to add to my journals in DayOne.

### YT to My Computer 

**What it does:** Takes a specified URL from the share sheet and uses Shortcuts to run a script over SSH to download the URL to a remote device (like your home computer) using [youtube-dl](rg3.github.io/youtube-dl). This is just a pretty basic script, but you can read their documentation [here](https://github.com/rg3/youtube-dl/blob/master/README.md) to see everything you can do with it. 😉

**Setup:** There’s basic setup questions to fill in your SSH settings like Host, Port, User & Password but **you’ll need to set up the path which you would like your media to download to manually.** Simply insert your desired path after `cd` with a location like `~\Downloads` or wherever you want! The script should look something like this: 

```
cd ~/Downloads
youtube-dl “$1”
```

* * *

Feel free to customize to your own preferences! And if you have any cool ideas or recommendations don't hesitate to let me know!
