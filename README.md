# Awesome Mastodon

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-9-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[<img src="https://user-images.githubusercontent.com/1534150/209670098-41dfd725-792e-4591-8097-52d70a09269a.svg" align="right" alt="Mastodon logo" width="150">](https://joinmastodon.org)

> Up-to-date and curated list of Mastodon-related stuff!

Forked from [tleb/awesome-mastodon](https://github.com/tleb/awesome-mastodon/edit/master/README.md) because that was no longer being updated.

**Mastodon is the world's largest free, open-source, decentralized microblogging network**. See the [Official](#official) category to learn more about the network.

## Contents

* [Official](#official)
* [Clients](#clients)
* [Lists](#lists)
* [Tools](#tools)
* [Browser Extensions](#extensions)
* [Guides](#guides)
* [Federated services](#federated-services)
* [Bots](#bots)
* [Libraries](#libraries)
* [FediAdmin](#fediadmin)
* [Contributors](#contributors)

## Official

* [Website](https://joinmastodon.org)
* [GitHub repository](https://github.com/mastodon/mastodon)
* [Documentation & official explaination](https://docs.joinmastodon.org/)
* [API documentation](https://docs.joinmastodon.org/client/intro/)

## Clients

### Web

* [Tooty](https://github.com/n1k0/tooty) - Experimental multi-account Mastodon Web client (Elm).
* [naumanni](https://github.com/naumanni/naumanni) - Web user interface specially designed for Mastodon.
* [Pinafore](https://github.com/nolanlawson/pinafore) - Alternative web client for Mastodon, focused on speed and simplicity. (no longer maintained)
  * [Semaphore](https://github.com/NickColley/semaphore) - a continuation of Pinafore
* [Brutaldon](https://git.carcosa.net/jmcbray/brutaldon) - Brutaldon is a brutalist, Web 1.0 web interface for Mastodon.
* [Halcyon](https://notabug.org/halcyon-suite/halcyon) - Alternative web client for Mastodon and Pleroma with a Twitter-like interface.
* [Planiverse](https://git.stjo.hn/planiverse/) - Minimalist, no-JS Web client for Mastodon.
* [Sengi](https://nicolasconstant.github.io/sengi/) - Desktop oriented webapp for Mastodon and Pleroma, focused on multi-accounts usages.
* [Phanpy](https://github.com/cheeaun/phanpy) - a minimalistic, opinionated web client for Mastodon
* [Hyperspace](https://hyperspace.marquiskurt.net/) - layout options such as a masonry layout (no longer maintained)
* [Elk](https://elk.zone) - a nimble Mastodon web client
* [Kaiteki](https://github.com/Kaiteki-Fedi/Kaiteki) - The comfy SNS client for everything, everywhere, available for Web, Windows, Linux and Android
* [Chirr App](https://getchirrapp.com/) - a web app that intelligently splits a long tweets into a thread; pro users [can crosspost their toots and threads to Mastodon](https://getchirrapp.com/new/2022-11-5)
* [Cuckoo+](https://www.cuckoo.social) - a GooglePlus-like third-party web client for Mastodon
* [Mastodeck](https://mastodeck.com/) - a Tweetdeck-like interface for Mastodon; 'advanced' interface with multiple verticle columns; highly customisable

### Mobile

* [Mastodon](https://joinmastodon.org/apps) - official Mastodon mobile app, available for both [Android](https://play.google.com/store/apps/details?id=org.joinmastodon.android) and [iOS](https://apps.apple.com/us/app/mastodon-for-iphone/id1571998974)
* [tooot](https://tooot.app/) - simple, elegant, open source mobile client, available for both [Android](https://play.google.com/store/apps/details?id=com.xmflsct.app.tooot) and [iOS](https://apps.apple.com/app/id1549772269)

Comparison lists:

- [Mastodon apps feature comparison](https://docs.google.com/spreadsheets/d/1De5KRwqMIdwEryfoeBLARgxF7QgKkeOQBCilKuIdAXE/edit#gid=0) - Collaborative Google sheet that provides a comparison of features across the various Android and iOS Mastodon apps


#### Android

* [Tusky](https://play.google.com/store/apps/details?id=com.keylesspalace.tusky) - Android client.
* [Twidere](https://f-droid.org/packages/org.mariotaku.twidere/) - Android app for Twitter, GNU Social and Mastodon.
* [Fedilab](https://framagit.org/tom79/fedilab) - Android client.
* [Subway Tooter](https://github.com/tateisu/SubwayTooter) - highly customisable Mastodon client for Android made by a Japanese developer
* [Husky](https://husky.adol.pw/) - Pleroma and Mastodon client for Android
* [Woolly](https://github.com/outadoc/woolly-app) - a Mastodon client built with Jetpack Compose and Compose Desktop
* [Yuito](https://github.com/accelforce/Yuito) - a Mastodon client forked from Tusky by a Japanese developer
* [Megalodon](https://github.com/sk22/megalodon) - a fork of the official Mastodon app adding certain features including the federated timeline, unlisted posting and an image description viewer
* [Moshidon](https://github.com/LucasGGamerM/moshidon) - a fork of the above-mentioned Megalodon app adding certain features and tweaks on top of Megalodon's features

#### iOS

* [Toot!](https://apps.apple.com/us/app/toot/id1229021451) - paid Mastodon client for iOS.
* [Metatext](https://metabolist.org/) - open source client for iOS; development has currently been suspended
* [Mercury for Mastodon](https://apps.apple.com/us/app/mercury-for-mastodon/id1486749200) - free Mastodon client for iOS
* [Mastoot](https://apps.apple.com/us/app/mastoot/id1501485410) - simple, free Mastodon client for iOS
* [Mast: for Mastodon](https://apps.apple.com/us/app/mast-for-mastodon/id1437429129) - paid Mastodon client for iOS
* [Mammoth](https://testflight.apple.com/join/HyL7boSn) - Mastodon client for iOS by the maker of Aviary for Twitter, still in beta
* [Ivory](https://tapbots.social/@ivory) - Mastodon client for iOS by Tapbots, still in alpha
* [Tootoise](https://apps.apple.com/us/app/tootoise/id1465090190) - simple Mastodon client for iOS, still in testing phase ([Testflight Link](https://testflight.apple.com/join/2LVAJQTP))
* [Tusker](https://vaccor.space/tusker/) - an iOS client for Mastodon and Pleroma; still a work in progress
* [Mona](https://mastodon.social/@MonaApp) - Mastodon client for iOS; still in testing phase
* [Tootle for Mastodon](https://apps.apple.com/us/app/tootle-for-mastodon/id1236013466) - an iPad Mastodon client
* [Woolly for Mastodon](https://mastodon.social/@mttvll/109546787074477406) - an iOS Mastodon client still in the early stages of development; available [on Testflight](https://testflight.apple.com/join/2LVAJQTP) only
* [Ice Cubes](https://github.com/Dimillian/IceCubesApp) - an iOS Mastodon client that is still under heavy development; available on [Testflight](https://testflight.apple.com/join/tqI3dK1u)
* [Trunk](https://mastodon.social/@davbeck/109509705243442173) - an iOS Mastodon client with a unique scrolling concept: Instead of scrolling vertically through your timeline, Trunk shows the full detail of each post, and you swipe right to left to go through the timeline. This may encourage better engagement and more focus on each individual post.
* [Mastoon](https://apps.apple.com/us/app/mastoon-for-mastodon/id1633757607) - a simple iOS Mastodon client

Sharing apps:

- [Linky](https://pragmaticcode.com/linky/) - lets you easily share webpage links, images and text extracts to Mastodon

#### SailfishOS

* [Tooter](https://github.com/dysk0/harbour-tooter) - Native client for SailfishOS.

### Desktop

* [Whalebird](https://whalebird.social/en/desktop/contents) - Electron-based cross-platform Mastodon client
* [Sengi](https://nicolasconstant.github.io/sengi/) - open source cross-platform Mastodon client
* [The Desk](https://thedesk.top/)
* [Elk Native](https://github.com/elk-zone/elk-native) - Native version of Elk, a nimble Mastodon web client

#### macOS

* [Mastonaut](https://apps.apple.com/us/app/mastonaut/id1450757574) - free macOS Mastodon client
* [Mast: for Mastodon](https://apps.apple.com/us/app/mast-for-mastodon/id1437429129) - paid macOS Mastodon client

#### Linux

* [Tootle](https://github.com/bleakgrey/tootle) - Simple Mastodon client designed for elementary OS.
* [Tokodon](https://apps.kde.org/en-gb/tokodon/) - open source KDE Plasma client

#### Emacs

* [mastodon.el](https://codeberg.org/martianh/mastodon.el) - Mastodon (+ Pleroma) client for Emacs.

### CLI

* [toot](https://github.com/ihabunek/toot) - Mastodon CLI client (Python).
* [madonctl](https://github.com/McKael/madonctl) - Mastodon CLI client (Go).
* [tut](https://github.com/RasmusLindroth/tut) - Mastodon TUI client (Go).

## Lists

### User Lists

- [Various Notable Accounts (Media, Politics, Tech, Ukraine, and more)](https://docs.google.com/spreadsheets/d/1XpBPzCFf0kI6aLnYyNPC74SJqI2SXg664sR3XrWDnfU/edit)
- [Academics on Mastodon](https://github.com/nathanlesage/academics-on-mastodon) - a list of academics on Mastodon
- [#LawFedi: Lawyers and Legal Academics on Mastodon](https://docs.google.com/spreadsheets/d/1nE8WxgwTFCuVeFA8ZfOW0qonJTSnI_d6EBSJ4E9JqtI/edit) - a list of lawyers and legal academics on Mastodon
- [FediPages](https://fedipages.com) - directory of Fediverse users
- [Public spreadsheet of popular/famous/notable Mastodon accounts](https://docs.google.com/spreadsheets/d/1cpUKkoT1MUn8_xM4usiERn-IdEuh0hXfBrwbbThwGiI/edit)
- [Mastodon Journalists and US Progressives](https://boskee.co.uk/mastodon-journalists/)
- [Journalists on Mastodon and Fediverse](https://docs.google.com/spreadsheets/d/13No4yxY-oFrN8PigC2jBWXreFCHWwVRTftwP6HcREtA/edit)
- [PressCheck](https://www.presscheck.org/) - find verified journalists on Mastodon
- [The Walt List](https://docs.google.com/spreadsheets/d/1rNfUosPSiMwRbUAbnI3h-7D9grP6ULgS/edit#gid=1301725065) - Walt Shaub’s list of prolific posters — mostly US politics
- [EduTooters Unite! - Mastodon #EduTooters and #K12Librarians Lists](https://docs.google.com/spreadsheets/d/1beJHWsuB0MJDMqeg_q8pBRWRdQImY-n8E6PttoJLFaM/edit)
- [FediFied](https://www.fedified.com/) - notable Twitter users now in the Fediverse
- [Trunk for the Fediverse](https://communitywiki.org/trunk) - a list of lists of users to follow
- [Fedi.Directory](https://fedi.directory/) - human-curated small selection of interesting accounts to help you get started on Mastodon and the Fediverse
- [Fediverse.info](https://fediverse.info/explore/people) - search for users who post about a certain topic

### Server Lists

* [Mastodon instances (instances.social)](https://instances.social/list) - List of Mastodon instances.
* [Mastodon server list](https://mastodonservers.net) - List of Mastodon server instances.
* [Mastodon quick scan spreadsheet](https://docs.google.com/spreadsheets/d/1hN-0bNfjaV7UTuLP6eudmXCNNPdeNQoFtbfcqxl4FFQ/edit#gid=0) - list of large and mid-size Mastodon instances
* [Fediverse Observer Mastodon List](https://mastodon.fediverse.observer/list)
* [FediDB Mastodon List](https://fedidb.org/network?s=mastodon)
* [mastodon-near-me](https://umap.openstreetmap.fr/en/map/mastodon-near-me_828094) - a visual map of Fediverse instances that operate primarily in or that are targeted towards specific territories, regions, or localities
* [#Education Friendly #Mastodon Instances](https://www.mguhlin.org/2022/11/education-friendly-mastodon-instances.html)
* [Fediversesearch](https://www.fediversesearch.com/) - search for instances
* [Fediverse.to](https://www.fediverse.to/) - fediverse instance search
* [Mapstodon](https://www.comeetie.fr/galerie/mapstodon/) - a graph visualisation of fediverse instances

## Tools

### Migration

* [Movetodon](https://www.movetodon.org/) - helps you locate the users you follow on Twitter who have Mastodon handles in their bios and allows you to follow them directly; no exporting and importing of CSVs required
* [Twitodon](https://twitodon.com/) - helps you locate the users you follow on Twitter who have Mastodon handles in their bios; exports a CSV that you can import into Mastodon
* [Fedifinder](https://fedifinder.glitch.me/) - helps you locate the users you follow on Twitter who have Mastodon handles in their bios; exports a CSV that you can import into Mastodon
* [Debirdify](https://debirdify.pruvisto.org/) - searches across the users you follow and your Twitter lists to locate users who have Fediverse handles; helps you identify instances relevant to your interests; exports a CSV that you can import into Mastodon

### Fediverse discovery

* [Fediverse Explorer](https://fediverse.0qz.fun/) - Trending hashtags and popular toots, regenerated every hour.
* [#FediBuzz](https://fedi.buzz/) - trending hashtags by language, live
* [Followgraph](https://followgraph.vercel.app) - find users followed by many of the people you follow
* [FediScope](https://eloquence.github.io/fediscope/) - find fediverse accounts for people in a field using Wikidata
* [FediSearch](https://fedisearch.skorpil.cz/feeds?search=) - Search for people across indexed instances, via their bio/name


### Toot discovery

* [unmung.com/mastoview](http://www.unmung.com/mastoview) - Preview the local or federated timeline of any instance.
* [mastodon_digest](https://github.com/hodgesmr/mastodon_digest) - Python script that aggregates recent popular posts from your Mastodon timeline 
* [fediview](https://fediview.com/) - web app that aggregates the recent popular posts from your Mastodon timeline
* [Quintessence](https://quintsns.pianeta.uno/) - web page that generates the latest links that have been shared the most among the people you follow
* [Blogofy](https://www.blogofy.com/) -  Search for hashtags across indexed instances, or discover currently trending hashtags across indexed instances

### Toot management

* [Forget](https://forget.codl.fr/about/) - Delete toots after a user defined period of time (Python [source code](https://github.com/codl/forget/)).
* [Toot scheduler](https://scheduler.mastodon.tools/) - Schedule now, toot later.
* [Thread counter by @axbom](https://xbm.se/fediverse/tc.php) - helps you split long posts into a numbered thread

#### Lists

* [hueyy/mastodon-lists-manager](https://mastodon-lists-manager.huey.xyz/) - tool for managing lists and followed users on Mastodon
* [Mastolists](https://mastolists.novaloop.cloud) - tool for managing lists (list view, matrix view and table view)
* [acbeers/mastodonlm](https://acbeers.github.io/mastodonlm/) - a simple list manager, bulit in the style of Twitter List Manager.

### Cross-posting

* [Mastodon Twitter Crossposter](https://crossposter.masto.donte.com.br/) - Service to crosspost to and from Twitter (rate-limited by Twitter to 300 per hour for the entire application)
* [Moa](https://moa.party/)
* [brandur/mastodon-cross-post](https://github.com/brandur/mastodon-cross-post) - golang script that crossposts tweets to Mastodon
* [AmauryCarrade/MastodonToTwitter](https://github.com/AmauryCarrade/MastodonToTwitter) - Mastodon ⬄ Twitter real-time cross-poster, using streaming APIs

### Webpage

* [emfed](https://github.com/sampsyo/emfed) - embed your Mastodon feed onto a web page
* [Last](https://framagit.org/luc/last) - aggregates toots on a web page providing Atom feed and an epub (Perl).

### Misc

* [emojis.in](https://emojos.in/) - view the custom emojis available on a Mastodon instance
* [Mastodon Link Debugger](https://mastodon-link-debugger.vercel.app/) - figure out why your links do not get verified
* [Mastinator](https://mastinator.com/) - disposable public anonymous no-login Fediverse accounts
* [Mastodon Bookmark RSS](https://bookmark-rss.services.woodland.cafe/) - expose your bookmarks as private RSS feed to read later, or for archival
* [Mastowatch](https://apps.apple.com/us/app/mastowatch/id1662271463) - iOS/macOS app that allows you to inspect the public config and details of any Mastodon server without having to log in or register

## Extensions

* [mastodon-simplified-federation](https://github.com/rugk/mastodon-simplified-federation) - Firefox extension that simplifies following or interacting with other users on remote Mastodon instances in the Fediverse
* [FediAct](https://github.com/Lartsch/FediAct) - Chrome / Firefox extension that simplifies follow and post interactions on Mastodon servers other than your own.
* [Mastodon Link](https://github.com/masrly/mastodon-link) - Chrome extension that adds a clickable mastodon icon next to mastodon usernames to visit their profile on your instance for ease of following
* [Mastodon View Profile](https://github.com/bramus/mastodon-view-profile) - Chrome extension that adds a button to the toolbar to visit a profile on your instance ease of following
* [Graze for Mastodon](https://graze.jaredzimmerman.com/) - Chrome & Firefox extension that enables 1-click follow, favorite, boost, and bookmark for Mastodon, no matter what instance you call home.
* [StreetPass](https://streetpass.social/) - an extension that collects `rel=me` links from websites that you visit so you can find people to follow on Mastodon based on the sites you visit

### Bookmarklets

* [Mastodon Toot Bookmarklet](https://rknightuk.github.io/mastodon-toot-bookmarklet/) - Bookmarklet to toot the current page ([source code](https://github.com/rknightuk/mastodon-toot-bookmarklet/))
* [Mastodon #nowplaying Toot Bookmarklet](https://nowplaying.resynth1943.net) - Bookmarklet to toot the music you're currently listening to. Works with YouTube. ([source code](https://github.com/resynth1943/mastodon-nowplaying-toot-bookmarklet))

### User styles

* [Variable width](https://userstyles.org/styles/139721/mastodon-glitch-soc-variable-width) - Makes Mastodon scale with the browser's width.
* [Narrow drawer](https://userstyles.org/styles/141457/mastodon-dynamic-wide-columns-narrow-drawer) - With the variable width style, makes the drawer narrower and the other columns scale accordingly.
* [Mastodon Modern](https://userstyles.world/style/4773/mastodon-modern) - Drastically improves the look & feel of Mastodon. Can be used with other themes that only change colors.
* [Mastodon Advanced View Plus](https://userstyles.world/style/7644/mastodon-advanced-view-plus) - Adds more options for Mastodon's advanced view.

### User scripts

* [NSFW Remover](https://greasyfork.org/fr/scripts/29228-mastodon-nsfw-remover) - Automatically display NSFW images.
* [Customizable interface](https://openuserjs.org/scripts/bl00m/Mastodon_Customizable_Interface) - Move and resize columns on a grid.
* [BirdSite](https://gitlab.com/pmorinerie/birdsite) - Browser extension for cross-posting Mastodon toots to Twitter.
* [MastoVue Embedded](https://git.kaki87.net/KaKi87/userscripts/src/branch/master/mastovueEmbedded/README.md) - MastoVue embedded into Mastodon.
* [Mastodon Redirector](https://git.kaki87.net/KaKi87/userscripts/src/branch/master/mastodonRedirector/README.md) - Redirect any Mastodon app to your favourite one.

## Guides

- [GuideToMastodon](https://github.com/joyeusenoelle/GuideToMastodon) - an increasingly less brief guide to Mastodon
- [Fedi.Tips](https://fedi.tips/) - informal, unofficial guide for non-technical people who want to use Mastodon and the wider Fediverse
- [A non-computer-person’s guide to how Mastodon instances work](https://scribe.rip/@jimpjorps/a-non-computer-persons-guide-to-how-mastodon-instances-work-da6ceac1994a)
- [TechCrunch: A beginner’s guide to Mastodon, the open source Twitter alternative](https://techcrunch.com/2022/11/08/what-is-mastodon/)
- [Clive Thompson: Come Join Me On Mastodon, Folks](https://clivethompson.scribe.rip/come-join-me-on-mastodon-folks-bbb073ff05d2)
- [Per Axbom: A Brief Mastodon Guide for Social Media Worriers](https://axbom.com/mastodon-guide/)
- [Mastodon Privacy Guide](https://github.com/clening/MastodonPrivacyGuide/) - a guide on data protection obligations, challenges & pitfalls for Mastodon users & instance admins
- [Mastodon 101 for Journalists](https://lisawilliams.github.io/lisa/tech/2022/11/28/mastodon-101-for-journalists.html)

### History

- [#MastodonNews Archive](https://docs.google.com/spreadsheets/d/1d5Q6oyzrlfXBEhHsLI9cxltdFV_XPrZWQj1mj8Ivc7Q/edit)
- [Twitter is Going Great!](https://twitterisgoinggreat.com/)
- [Mastodon: a partial history](https://privacy.thenexus.today/mastodon-a-partial-history/)

## Federated services

### Microblogging

* [Mastodon](https://joinmastodon.org/) - Most popular microblogging platform.
  * [Mastodon Glitch Edition (glitch-soc)](https://glitch-soc.github.io/docs/) - a Mastodon fork with additional features such as rich text formatting and local-only toots
  * [Hometown](https://github.com/hometown-fork/hometown) - a lightweight fork of Mastodon that supports local-only toots and more content types
* [GnuSocial](https://gnu.io/social/) - Oldest microblogging platform.
* [Pleroma](https://pleroma.social/) - Lightweight, customisable microblogging platform.
  * [Akkoma](https://akkoma.social/) - a Pleroma fork with more features and a faster pace of development
* [Misskey](https://misskey-hub.net/en/) - feature-packed microblogging platform; supports reactions to posts
  * [Calckey](https://codeberg.org/calckey/calckey) - fork of Misskey with better UI/UX, security, features, etc
  * [Foundkey](https://akkoma.dev/FoundKeyGang/FoundKey) - fork of Misskey that improves on maintainability and behaviour, while also bringing in useful features.
* [Microblog.pub](https://microblog.pub/) - Single-user lightweight microblogging platform.
* [NextCloud Social](https://apps.nextcloud.com/apps/social) - Microblogging app for the Nextcloud platform.
* [GotoSocial](https://github.com/superseriousbusiness/gotosocial) - fast and efficient ActivityPub server written in Golang, still in alpha
* [Takahē](https://jointakahe.org/) - an efficient ActivityPub server for microblogging with multiple support for multiple domains

### Blogging

* [Plume](https://joinplu.me/) - Blogging platform.
* [WriteFreely](https://writefreely.org/) - Blogging platform.
* [WordPress ActivityPub](https://wordpress.org/plugins/activitypub/) - WordPress plugin for adding ActivityPub support to any WordPress site
* [Drupal ActivityPub](https://www.drupal.org/project/activitypub) - Drupal module that implements ActivityPub on a Drupal site

### Link aggregation

* [Prismo](https://gitlab.com/prismosuite/prismo) - Link aggregation platform.
* [Lemmy](https://join-lemmy.org/) - Reddit-like link aggregator and forum

### Others

* [Friendica](https://friendi.ca/) - Facebook/Myspace-like social network platform.
* [PixelFed](https://pixelfed.org/) - Instagram-like photograph sharing platform.
* [Peertube](https://joinpeertube.org/) - Youtube-like video sharing platform.
* [FunkWhale](https://funkwhale.audio/) - Soundcloud-like audio sharing platform.
* [Hubzilla](https://zotlabs.org/page/hubzilla/hubzilla-project) - Blog/social networks platform with file, contacts and events sharing.
* [BookWyrm](https://joinbookwyrm.com/) - Goodreads/Librarything-like book social network.

## Bots

* [usercount](https://github.com/josefkenny/usercount) - Bot which posts user statistics to Mastodon (Python).
* [autofollow](https://github.com/gled-rs/mastodon-autofollow) - Autofollow bot for Mastodon (Python).
* [hnbot](https://github.com/raymestalez/mastodon-hnbot) - Posts the Hacker News stories with 100+ points (Python).
* [translator](https://christopher.su/projects/translator/) - Translate any toot into the desired language using `@translator@toot.works [langcode]`.
* [@TrendingBot@mastodon.social](https://mastodon.social/@TrendingBot) - Shows you what's trending on Mastodon.
* [Remindr](https://gitlab.com/chaica/remindr) - Automatically send reminders to both Mastodon and Twitter from a list of resources (Python).
* [News Bot](https://botsin.space/@newsbot) - mirrors Twitter accounts on Mastodon (ClojureScript), source available on [GitHub](https://github.com/yogthos/mastodon-bot).
* [Welcome Bot](https://github.com/indyhall/mastodon-welcome-bot) - Automatically send a welcome DM to new users (Python).

### RSS

* [feed2toot](https://gitlab.com/chaica/feed2toot) - Automatically parses RSS feeds, identifies new posts and posts them on Mastodon (Python).
* [rss-to-activitypub](https://github.com/umonaca/rss-to-activitypub) - not a bot, but a simple server that converts an RSS feed into an ActivityPub actor that can be followed on Mastodon 
* [MastoFeed](https://mastofeed.org/) - automated and super easy tool to send the content from your RSS Feeds to any Mastodon instance
* [feediverse](https://github.com/edsu/feediverse) - Python script that posts RSS feed items to ActivityPub

## Libraries

### Python

* [Mastodon.py](https://github.com/halcy/Mastodon.py) - Python wrapper for the Mastodon API.
* [atoot](https://github.com/popura-network/atoot) - asynchronous Python client library for the Mastodon API

### Javascript

* [Megalodon](https://github.com/h3poteto/megalodon) - Mastodon API client library for node.js.

### PHP

* [ActivityPHP](https://github.com/landrok/activitypub) - PHP implementation of ActivityPub

### Golang

* [go-mastodon](https://github.com/mattn/go-mastodon) - Mastodon client library for Golang
* [madon](https://github.com/McKael/madon) - Golang client library for the Mastodon API

### Kotlin

* [mastodonk](https://github.com/outadoc/mastodonk) - Mastodon client library for Kotlin

### Clojure

* [thefox](https://github.com/valerauko/thefox) - incomplete and unmaintained Clojure library for handling ActivityPub interactions

### Embedded systems

* [Lyuba](https://github.com/ringtailsoftware/lyuba) - Arduino library for tooting and retrieving toots matching a certain hashtag

## FediAdmin

### Managed hosting

* [Masto.host](https://masto.host) - Fully managed Mastodon hosting.
* [WebApe](https://webape.site/) - German-based Mastodon hosting service; also provides PeerTube, Nextcloud, Friendica, Matrix, Jitsi Meet, CryptPad and WordPress hosting
* [toot.io](https://toot.io/mastodon_hosting.html) - Mastodon hosting service that serves HPC at University of Texas Austin, Association for Computing Machinery (ACM), amongst others
* [IKNOX](https://iknox.com/products/mastodon-hosting)
* [HostDon](https://hostdon.jp/#/) - Japan-based Mastodon hosting service
* [SpaceBear](https://federation.spacebear.ee/software/mastodon)
* [CloudPlane](https://cloudplane.org/)
* [Fedi Monster](https://fedi.monster/) - Mastodon hosting service; supports hosting glitch-soc and Hometown forks; also provides Pixelfed and GotoSocial hosting
* [Ossrox](https://ossrox.org/) - German-based Mastodon hosting service; also provides Peertube, Matomo, Cryptpad, Matrix, and Jitsi Meet hosting, amongst others
* [ungleich](https://ungleich.ch/u/products/mastodon-hosting/) - Mastodon hosting service based in Switzerland

### VPCs

* [DigitalOcean Mastodon Droplet](https://marketplace.digitalocean.com/apps/mastodon)
* [Linode Mastodon App](https://www.linode.com/marketplace/apps/linode/mastodon-server/)


### Tools

* [FakeRelay](https://github.com/g3rv4/FakeRelay) - tool for Mastodon admins to load statuses from other instances into their own instance
* [RelayList](https://relaylist.com) - A list of relays that can be added to a Mastodon, Misskey, or Pleroma server.

### Guides

* [rixx.de: On Running a Mastodon Instance](https://rixx.de/blog/on-running-a-mastodon-instance/)
* [EFF: User Generated Content and the Fediverse - A Legal Primer](https://www.eff.org/deeplinks/2022/12/user-generated-content-and-fediverse-legal-primer)

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/hueyy"><img src="https://avatars.githubusercontent.com/u/6523121?v=4?s=50" width="50px;" alt="Huey"/><br /><sub><b>Huey</b></sub></a><br /><a href="#maintenance-hueyy" title="Maintenance">🚧</a> <a href="#content-hueyy" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/magbeat"><img src="https://avatars.githubusercontent.com/u/1089410?v=4?s=50" width="50px;" alt="Markus Huggler"/><br /><sub><b>Markus Huggler</b></sub></a><br /><a href="#content-magbeat" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ctbk"><img src="https://avatars.githubusercontent.com/u/5497382?v=4?s=50" width="50px;" alt="Stefano Bonora"/><br /><sub><b>Stefano Bonora</b></sub></a><br /><a href="#content-ctbk" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/wiegelmann"><img src="https://avatars.githubusercontent.com/u/6149471?v=4?s=50" width="50px;" alt="jan"/><br /><sub><b>jan</b></sub></a><br /><a href="#content-wiegelmann" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/untitaker"><img src="https://avatars.githubusercontent.com/u/837573?v=4?s=50" width="50px;" alt="Markus Unterwaditzer"/><br /><sub><b>Markus Unterwaditzer</b></sub></a><br /><a href="#content-untitaker" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mooseyboots"><img src="https://avatars.githubusercontent.com/u/66318400?v=4?s=50" width="50px;" alt="mooseyboots"/><br /><sub><b>mooseyboots</b></sub></a><br /><a href="#content-mooseyboots" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://indiealexh.com"><img src="https://avatars.githubusercontent.com/u/1066212?v=4?s=50" width="50px;" alt="Alexander Haslam"/><br /><sub><b>Alexander Haslam</b></sub></a><br /><a href="#content-indiealexh" title="Content">🖋</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://git.kaki87.net/KaKi87"><img src="https://avatars.githubusercontent.com/u/21284089?v=4?s=50" width="50px;" alt="KaKi87"/><br /><sub><b>KaKi87</b></sub></a><br /><a href="#content-KaKi87" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://fosstodon.org/@Nive9"><img src="https://avatars.githubusercontent.com/u/29470670?v=4?s=50" width="50px;" alt="Kevin"/><br /><sub><b>Kevin</b></sub></a><br /><a href="#content-Nive9" title="Content">🖋</a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td align="center" size="13px" colspan="7">
        <img src="https://raw.githubusercontent.com/all-contributors/all-contributors-cli/1b8533af435da9854653492b1327a23a4dbd0a10/assets/logo-small.svg">
          <a href="https://all-contributors.js.org/docs/en/bot/usage">Add your contributions</a>
        </img>
      </td>
    </tr>
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
