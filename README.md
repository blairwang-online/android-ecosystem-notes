# android-ecosystem-notes

## Preamble

I switched back to an Android phone as my main device in early 2025, from having been on iPhone for several years; and oh my, it is a very different ecosystem now!

## App Stores and notable apps therein

In order of preference:

### 1. Accrescent

Open source and relatively more secured / relatively more closed ecosystem. https://github.com/accrescent/accrescent

Notable apps:

- ⭐️ Aves Gallery
	- One of the better 'Gallery' apps out there, I found it a bit easier to get going with compared to (admittedly also very good) Fossify Gallery and IacobIonut01's Gallery
	- https://github.com/deckerst/aves

- ⭐️ IronFox
	- Android Firefox fork, similar role to LibreWolf on desktop environments in light of [recent Mozilla controversies](https://www.pcgamer.com/gaming-industry/mozilla-is-already-trying-to-backtrack-on-firefoxs-controversial-data-privacy-update-but-it-might-be-too-little-too-late/)
	- https://gitlab.com/ironfox-oss/IronFox
	
- 🤔 Organic Maps
	- Promising but not as established as OsmAnd just yet

### 2. Obtainium

Goes to Git repos and fetches APK from the releases section. https://github.com/ImranR98/Obtainium

Notable apps:

- ⭐️ Breezy Weather
	- Just a very nice weather app, responsive and extensive similar to the stock Weather app on iOS
	- https://github.com/ImranR98/Obtainium

- ⭐️ Doable
	- Simple, responsive, 'Material You' todo list app
	- Backup to NextCloud filesystem: what you get is a folder with JSON files that you can view; but from my experience, any changes you make upstream don't get propagated back to the app
	- https://codeberg.org/florian-obernberger/flutter-doable

- ⭐️ FUTO Keyboard
	- From what I can see so far, at time of writing, the only open-source keyboard that has glide-typing ('swipe'-typing)
	- https://github.com/futo-org/android-keyboard

- ⭐️ Habits
	- Daily habit tracking, conceptually similar to, e.g., Habitify on iOS
	- https://github.com/iSoron/uhabits
	
- ⭐️ Read You
	- Very neat, 'Material You' RSS app
	- https://github.com/Ashinch/ReadYou

- ⭐️ Stratum
	- Very neat Authenticator app (equiv. Duo, Microsoft Authenticator, etc.)
	- Known issue with QR code scanning ([#1249](https://github.com/stratumauth/app/issues/1249), they're working on it), provided key works though
	- https://github.com/stratumauth/app
 
- 🤔 Gallery by IacobIonut01
	- Generally nice, I did find Aves a bit more suited to my needs, but this one is very nice too
	- https://github.com/IacobIonut01/Gallery

### 3. F-droid

Basically an online collection of APKs, there is some effort towards security hardening but I think Accrescent and Obtainium models are a bit tighter at this point.

Notable apps:

- ⭐️ OsmAnd
	- More feature-rich alternative to 'My Tracks'
	- https://f-droid.org/en/packages/net.osmand.plus/

- 🤔 KDE Apps
	- Very interesting concept of developing apps that work on both desktop Linux and mobile Android
	- Very functional, isn't as responsive as native apps on Android, but it's a great endeavour
	- https://apps.kde.org/platforms/android/

### 4. Google Play Store

I'll use this but lean towards open-source options.

- ⭐️ Fossify apps
	- Open-source alternatives to stock apps which are increasingly tied to Google cloud services
	- Contacts, Messages, Phone, & Voice Recorder are excellent
	- Calendar is nice, I did find aCalendar+ a bit more suited to my needs, but this one is very nice too
	- Clock is nice, I did find that the Google Clock app had some features that make a big difference, but this one is very nice too
	- Files is nice, I did find that Material Files is more suited to my needs (esp. connecting to SMB servers), but this one is very nice too
	- Gallery is nice, I did find Aves a bit more suited to my needs, but this one is very nice too
	- https://github.com/FossifyOrg/

- ⭐️ GitJournal
	- Like Markor, but instead of working with a folder on the local filesystem and requiring a sync agent like Dropsync, this one directly commits onto a Git repo
	- https://github.com/GitJournal/GitJournal

- ⭐️ LocalSend
	- AirDrop alternative (admittedly only works if you're on the same LAN, but works really nicely for home use)
	- https://github.com/localsend/localsend

- ⭐️ Markor
	- Just a very simple straightforward Markdown editor (e.g., to work with an FSNotes-style collection of notes)
	- https://github.com/gsantner/markor

- ⭐️ Simple QR by Tom Fong
	- Just a very simple straightforward QR code scanner
	- Unlike the camera app, I can copy to clipboard instead of activating the URL
	- https://github.com/tomfong/simple-qr

- 🧧 aCalendar+
	- Calendar app with very innovative layout, developer based in Germany (European Union)
	- Free version and Paid version (approx. 10 EUR) available
	- Developer: Tapir Apps, Munich, Germany 🇩🇪🇪🇺 https://www.tapirapps.de/en/about
	- https://play.google.com/store/apps/details?id=org.withouthat.acalendar (Free version)
	- https://play.google.com/store/apps/details?id=org.withouthat.acalendarplus (Paid version)

- 🧧 DAVx5
	- CalDAV and CardDAV (i.e., calendar and contacts) synchronisation agent, great for synchronising with NextCloud, developer based in Austria (European Union)
	- Paid (approx. 6 EUR)
	- Developer: bitfire web engineering GmbH, Bad Vöslau, Austria 🇦🇹🇪🇺 https://www.bitfire.at/
	- https://play.google.com/store/apps/details?id=at.bitfire.davdroid

- 🧧 DropSync
	- Synchronisation agent, great for synchronising with NextCloud, developer based in Czech Republic (European Union)
	- Free version and Paid version (approx. 7 EUR) available
	- Developer: MetaCtrl, Prague, Czech Republic 🇨🇿🇪🇺 https://metactrl.com/
	- https://play.google.com/store/apps/details?id=com.ttxapps.dropsync (Free version)
	- https://play.google.com/store/apps/details?id=com.ttxapps.dropsync.pro (Paid version)

- 🧧 Niagara Launcher
	- Excellent minimalistic launcher, super clean and efficient
	- Freemium model (in-app subscription/purchase, [pricing information](https://help.niagaralauncher.app/article/104-price-of-niagara-pro))
	- Developer based in Germany (European Union) 🇩🇪🇪🇺
	- https://play.google.com/store/apps/details?id=bitpit.launcher

- 🧧 Timely
	- Excellent countdown app, clean and efficient, functionally equivalent to Bears Countdown on iOS (sadly without the bears)
	- Developer based in Germany (European Union) 🇩🇪🇪🇺
	- Paid (approx. 1 EUR)
	- https://play.google.com/store/apps/details?id=xyz.ptgms.countdown

## Configuration

### microSD card

Note that this is not encrypted so I would only use the microSD card to store consumer multimedia content, not personal or private or business data.

- **Disney+:** tap your profile picture in the bottom-right corner &rarr; App Settings &rarr; Download Location &rarr; External Storage
- **OsmAnd:** main menu &rarr; Settings &rarr; OsmAnd settings (Effective for the entire app) &rarr; Data storage foler &rarr; External storage X (where X is probably like, 2)
- **Netflix:** tap your profile picture in the bottom-right corner &rarr; hamberger menu in the top-right corner &rarr; App Settings &rarr; Download Location &rarr; SD Card
- **Pocket Casts:** Profile &rarr; gear icon (top-right corner) &rarr; Storage & data use &rarr; Storage podcasts on &rarr; SD Card
- **Spotify:** tap your profile picture &rarr; Settings and privacy &rarr; Data-saving and offline &rarr; scroll to the bottom &rarr; Storage location &rarr; SD card
