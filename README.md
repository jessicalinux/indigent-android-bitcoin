# indigent-android-bitcoin

A guide to setting up a stock android device as a mobile bitcoin appliance for people with few resources. The initial target is to provide a smooth process for panhandlers to receive bitcoin tips.

## Tip4Commit

This project participates in [Tip4Commit](https://tip4commit.com/github/secret-bitcoin-login/indigent-android-bitcoin). Feel free to submit pull requests, or contribute to the project by donating to [1JmQ9va35LJsmw8ob7seXDnz5Jzfo42NqC](bitcoin://1JmQ9va35LJsmw8ob7seXDnz5Jzfo42NqC)

[![tip for next commit](https://tip4commit.com/projects/43146.svg)](https://tip4commit.com/github/secret-bitcoin-login/indigent-android-bitcoin) 

## The scenario

Bitcoin has huge potential with people of little means to conduct personal banking and exchange. The barriers to entry have been helping those in need understand bitcoin and finding a way to help them earn/receive bitcoin. If givers could easily view those in need, it would be easier to provide tips, wages, and gifts just by looking at their names on the screen. The bitholla app adds this functionality by providing a geolocated list of persons.

## The tools

Begin with an android device that has been factory reset and cleared of any carrier bloatware. I have added links to the files, but I encourage you to install using the Google Play store so the end user will get updates.

* [READ_THIS.txt](https://raw.githubusercontent.com/secret-bitcoin-login/indigent-android-bitcoin/master/READ_THIS.txt) - an introduction to the phone that will be linked on the home screen
* [Bitholla](https://play.google.com/store/apps/details?id=com.me.bit.bitme) - Bitholla is the geolocation send/receive app (not a wallet)
* [Reddit browser](https://play.google.com/store/apps/details?id=com.andrewshu.android.reddit) - Reddit is fun to develop community
* [Gyft](https://play.google.com/store/apps/details?id=com.gyft.android) - Practical use of bitcoin
* [Mycelium Wallet](https://play.google.com/store/apps/details?id=com.mycelium.wallet) - The primary bitcoin wallet on the device
* [Circle Wallet](https://play.google.com/store/apps/details?id=com.circle.android) - Some people will want to link to banking
* Introduction Video - Morgan Spurlock - "Inside Man" S03E05 - Bitcoin. Source this on your own, or choose an alternative.
* [ES File Exlorer](https://play.google.com/store/apps/details?id=com.estrongs.android.pop) - This allows you to select a file and easily create a link to the desktop
* [Nova Launcher](https://play.google.com/store/apps/details?id=com.teslacoilsw.launcher) - A good simple launcher that isn't difficult to use
* [Offline Street Maps](https://play.google.com/store/apps/details?id=cz.aponia.bor3.offlinemaps) - Open Streetmaps offline maps - be sure to download your current area maps during setup.
* Need to add a WiFi finding service, currently experimenting with [Instabridge](https://play.google.com/store/apps/details?id=com.instabridge.android). Please provide any ideas or useful information.

## Device Setup

![Example homescreen](iab.png)

1. Turn the device on airplane mode but enable WiFi.
2. Create a google account with a memorable name and secure password. I suggest making a physical copy of this username and password and somehow pasting it/taping to to the outside of the device.
3. Set up a mycelium account. Make physical backup of the seed for the end user and store in with the device.
3. Set up a Bitholla account, in the username, append _ind to any name you choose, this will help others know that the phone is requesting indigent donations. Use the mycelium account to fund the bitholla account. (Bitholla is NOT a wallet, it is a convenience layer.)
4. Set up a reddit account using the same username. Unsubscribe from the defaults, and subscribe to /r/btc and your local reddits.
5. Set up a Gyft account and connect it to the Google+ account.
6. Clear the desktop and install a simple launcher (Nova launcher?)
7. Find a way to get the [READ_THIS.txt](https://raw.githubusercontent.com/secret-bitcoin-login/indigent-android-bitcoin/master/READ_THIS.txt) file on the phone - it may be easiest to download from the github, I use adb.
7. Open ES File explorer and create shortcuts on the desktop for READ_THIS.txt and the morgan spurlock "Inside Man" episode.

## About Bitholla

This github has absolutely no affiliation with bitholla other than product interest. You can reach out to bitholla at http://bitholla.io

## Media Coverage

[Bitholla for the Homeless: Why One Mystery Man Gives Away His Bitcoin](https://news.bitcoin.com/bitholla-homeless-one-mystery-man-gives-away-bitcoin/)

## The project in use

* Please share details of any examples and we'll post them here.
