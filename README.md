# Multi Platform Kapu Lite Client

## Download
[Latest Release](https://github.com/kapucoin/kapu-desktop/releases)

## Features
* Available on ***Windows***, ***Linux*** (ubuntu/debian) and ***Macosx*** (signed)
* No wait to sync to the network: launch and use.
* view any account from its address (transactions, delegate status and votes)
* (soon) deposit KAPU using altcoins or USD (via changer.com) - no registration needed
* label any account
* realtime currency value (updated every 5 min) in UsD, Euro, BTC, HKD, JPY, CNY, AuD, CanD, Pound and Rubble
* autoconnecting to a healthy kapu network peer. If the peer is not good any more, automatically find a new one.
* send kapu from/to any account.
* easily switch to different network, or private chains
* customize background
* isolated processes on Windows and Macosx to prevent from data sniffing or injection.
* Translations (thanks to the kapu community). Please help contributing

If you login to your account (with your passphrase)
* (soon) Withdraw to altcoins or USD (via changer.com) - no registration needed
* Organise your accounts with virtual folders (for instance savings, personnal etc...) so you don't pay any transfer fee
* Update your votes.
* Save your passphrases (unsecured so far, secured vault in the near future)

Second signature supported. Multisignature accounts not yet supported.

## Screenshots
![linux](http://i.imgur.com/snJi21i.jpg)
![linux](http://i.imgur.com/gjjqw88.jpg)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fkapucoin%2Fkapu-desktop.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fkapucoin%2Fkapu-desktop?ref=badge_shield)

## From code

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. Optionally switch to node 6.9.2, because this is currently developped with this version:
```
sudo npm install -g n
sudo n 6.9.2
```

Install from source:
```bash
# Clone this repository
git clone https://github.com/kapucoin/kapu-desktop
# Go into the repository
cd kapu-desktop
# Install dependencies 
npm install
npm run postinstall
```

Then start:
```bash
npm start
```

## Necessary to package from Ubuntu
```
apt-get install icnsutils
apt-get install imagemagick
```

## Necessary to package from Mac OS X

```
brew tap Homebrew/bundle
brew bundle
```

## Authors
- FX Thoorens <fx@ark.io>
- Guillaume Verbal <doweig@ark.io>

### License [MIT](LICENSE.md) copyright (c) 2016 KAPU, copyright (c) 2016 fx thoorens


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fkapucoin%2Fkapu-desktop.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fkapucoin%2Fkapu-desktop?ref=badge_large)