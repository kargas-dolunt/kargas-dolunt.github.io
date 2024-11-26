---
title: Technology
layout: default
parent: Solarpunk
created: 2023-10-17T13:37:47 (UTC -04:00)
source: https://wiki.sunbeam.city/doku.php?id=technology
tags:
  - technology
---

## Decentralisation

-   _Contribute links or articles to this topic_
    
-   [Walkaway Wiki](https://walkaway.wiki/ "https://walkaway.wiki/") “this handbook is a prototype-in-progress for a much cooler peer-to-peer wiki system. our goal is to create a solarpunk “library of alexandria” that lives in a distributed mesh”
-   [Build One Army](https://build.onearmy.world/ "https://build.onearmy.world/") “We’re building a platform for communities to grow online/offline and tackle global problems.”

## Metadata Resistance

-   [Metadata Resistance](https://wiki.sunbeam.city/doku.php?id=metadata_resistance "metadata_resistance") is an actively-in-development area of work for privacy, defending against a now-primary vector of government and corporate surveillance.
-   [Privacy International](https://privacyinternational.org/campaigns/phone-data-extraction "https://privacyinternational.org/campaigns/phone-data-extraction") warns that the police can extract your data from your phone  
-   [European observatory on Algorithmic Sovereignty](https://algosov.org/ "https://algosov.org/")

### How-Tos

-   [Surveillance Self-Defense - Tips, Tools and How-tos for Safer Online Communications](https://ssd.eff.org/ "https://ssd.eff.org/")
-   [Digital self-defense workshop - on tour, workshop on support on the Gira Zapatista](https://videos.coletivos.org/videos/watch/d1463b7c-15d7-443d-a10b-4c0d796a228c "https://videos.coletivos.org/videos/watch/d1463b7c-15d7-443d-a10b-4c0d796a228c")
-   [Security in a Box – Digital-security tools & tactics](https://securityinabox.org/en/ "https://securityinabox.org/en/") The Tactics Guides in this toolkit cover basic principles such as how to create strong passphrases and avoid malware.

—-

## Anonymity Networks

-   [I2P](https://geti2p.net/ "https://geti2p.net/") - The Invisible Internet Project (I2P) is a FLOSS anonymous network layer that allows for censorship-resistant, peer to peer communication. Anonymous connections are achieved by encrypting the user's traffic (by using end-to-end encryption), and sending it through a volunteer-run network of roughly 55,000 computers distributed around the world. Given the high possibility of paths the traffic can transit, a third party watching a full connection is unlikely. The software that implements this layer is called an “I2P router”, and a computer running I2P is called an “I2P node”.
-   [Tor](https://www.torproject.org/ "https://www.torproject.org/") - The Onion Router (Tor) is FLOSS for enabling online anonymity. Tor directs Internet traffic through a free, worldwide, volunteer network consisting of more than seven thousand relays to conceal a user's location or usage from anyone conducting network surveillance or traffic analysis. Using Tor makes it more difficult to trace Internet activity, including “visits to Web sites, online posts, instant messages, and other communication forms”, back to the user and is intended to protect the personal privacy of users, as well as their freedom and ability to conduct confidential business by keeping their internet activities from being monitored.
    

___

## Instant Messaging

Secure instant messaging is a specialized form of instant messaging that along with other differences, encrypts and decrypts the contents of the messages such that only the actual users can understand them.

-   [Element](https://element.io/ "https://element.io/") - A secure collaboration app for group chat, file transfer and voice/video conferencing built on the decentralized Matrix ecosystem, providing bridges and integrations to centralized services such as IRC, Slack, Gitter, etc
-   [XMPP](https://xmpp.org/ "https://xmpp.org/") - Extensible Messaging and Presence Protocol (XMPP) is a communication protocol for message-oriented middleware such as Psi+ (Desktop), Conversations (Android) and ChatSecure (iOS). It enables the near-real-time exchange of structured yet extensible data between any two or more network entities. audits on conversations [2016](https://conversations.im/omemo/audit.pdf "https://conversations.im/omemo/audit.pdf") / omemo [2021](https://teddit.net/r/netsec/comments/o1q0jn/public_crypto_audit_report_lurchomemo/ "https://teddit.net/r/netsec/comments/o1q0jn/public_crypto_audit_report_lurchomemo/").
-   [Signal](https://signal.org/ "https://signal.org/") For mobile devices running Android or iOS, the open source Signal app offers end-to-end encrypted voice, video, text, and photos, and it's been endorsed by security and cryptography experts including Edward Snowden and Bruce Schneier and the Electronic Frontier Foundation. Can we trust signal? Signal is a centralized network. Very suitable of Man-in-the-middle attacks! [Signal big flaws](https://sequoia-pgp.org/blog/2021/06/28/202106-hey-signal-great-encryption-needs-great-authentication/ "https://sequoia-pgp.org/blog/2021/06/28/202106-hey-signal-great-encryption-needs-great-authentication/")
-   [OpenPGP](https://ssd.eff.org/en/module/how-use-pgp-linux "https://ssd.eff.org/en/module/how-use-pgp-linux") for sending encrypted emails. And some concerns on PGP[Let PGP Die: Why We Need a New Standard for Email Encryption](https://restoreprivacy.com/let-pgp-die/ "https://restoreprivacy.com/let-pgp-die/")
    

___

## Media Publishing

Publishing is the dissemination of literature, music, or information — the activity of making information available to the general public.

-   [PeerTube](https://joinpeertube.org/ "https://joinpeertube.org/") - A FLOSS decentralized federated video hosting network that uses peer-to-peer technology to reduce load on individual servers.
-   [Pixelfed](https://pixelfed.org/ "https://pixelfed.org/") - Federated image sharing.
-   [WriteFreely](https://writefreely.org/ "https://writefreely.org/") - A FLOSS federated blogging platform.
-   [dat](https://datproject.org "https://datproject.org") - Dat is a way to share data with a group of people in something that's like an editable bit-torrent. Peers host your data when they view it. Some people host sketchbooks there, other folks store interesting civic data sets. You can view dat files with, among other things, [the Beaker Browser](https://beakerbrowser.com/ "https://beakerbrowser.com/")
-   [Free your stuff](https://freeyourstuff.cc "https://freeyourstuff.cc") - makes it easy to share your content on supported sites
    

___

## Mesh Networks

A mesh network is a decentralized peer-to-peer network, with user-controlled physical links that are usually wireless, where each node must not only capture and disseminate its own data, but also serve as a relay for other nodes, that is, it must collaborate to propagate the data in the network.

-   [Cjdns](https://github.com/cjdelisle/cjdns "https://github.com/cjdelisle/cjdns") - Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks. Instead of letting other computers connect to you through a shared IP address which anyone can use, cjdns only lets computers talk to one other after they have verified each other cryptographically.
-   [tinc](http://tinc-vpn.org/ "http://tinc-vpn.org/") - tinc is a Virtual Private Network (VPN) daemon that uses tunnelling and encryption to create a secure private network between hosts on the Internet. Because the VPN appears to the IP level network code as a normal network device, there is no need to adapt any existing software. This allows VPN sites to share information with each other over the Internet without exposing any information to others.
-   [Commotion Wireless](https://commotionwireless.net/ "https://commotionwireless.net/") - Software and how-tos for meshnets.
-   [Buildyourowninter.net's list of active meshnets](https://buildyourowninter.net/networks.html "https://buildyourowninter.net/networks.html") - Join an existing network!
-   [Darknetmap](http://darknetmap.zone42.ca/ "http://darknetmap.zone42.ca/") - A map of interest in meshnets. Place a pin to let other people know you want to start a network in your area!
-   [LibreMesh](https://libremesh.org/ "https://libremesh.org/") - Meshnet firmware for existing routers, designed to make it as easy as possible for users to create a network.
-   [Makerplex](https://tkcooptech.tumblr.com/post/176848160665/the-makerplex-is-essentially-an-open-source "https://tkcooptech.tumblr.com/post/176848160665/the-makerplex-is-essentially-an-open-source") “The “Makerplex” is essentially an open source combination of makerspace, market, factory, public resource, educational facility, and research/development lab.”

### How-Tos

-   [Community Technology](https://communitytechnology.github.io/ "https://communitytechnology.github.io/") - An in-depth, wiki-style library of meshnet guides and resources.
-   [Wireless Networking in the Developing World](http://wndw.net/ "http://wndw.net/") - A free book about designing, implementing, and maintaining low-cost wireless networks.
-   [Pretty Fly For A Wi-Fi](https://roelof.info/projects/(2014)Pretty_Fly_For_A_Wifi/Pretty_Fly_For_A_Wi-Fi_booklet.pdf "https://roelof.info/projects/(2014)Pretty_Fly_For_A_Wifi/Pretty_Fly_For_A_Wi-Fi_booklet.pdf") - Homemade wifi antennae, collected and tested, with instructions for each.
-   [Open Source Low Tech dish](https://solarflower.blogspot.com/2011/07/chicken-mesh-and-plywood-radiowifi.html "https://solarflower.blogspot.com/2011/07/chicken-mesh-and-plywood-radiowifi.html") - A cheap DIY wifi dish made of scrap plywood and chicken mesh.
-   [USB descriptors project](https://github.com/PuppyPi/usb-descriptors-project "https://github.com/PuppyPi/usb-descriptors-project") Catalog all known USB descriptors in a semantic (programmatically-accessible) format!
    

___

## Peer-to-Peer Software

Peer-to-peer software sends information directly from one device to another without passing through or being stored on any central server. This keeps your information private and safe, since all data is stored on multiple individual's devices.

-   [Scuttlebutt](https://www.scuttlebutt.nz/ "https://www.scuttlebutt.nz/") - A FLOSS peer-to-peer social network. Scuttlebutt can be used offline or through any kind of connection (internet, meshnet, sneakernet, wifi, etc). Also has an Android app, [Manyverse](https://www.manyver.se/ "https://www.manyver.se/").
-   [Briar](https://briarproject.org/ "https://briarproject.org/") - A peer-to-peer encrypted messaging app for Android.
-   [Dark Crystal](https://darkcrystal.pw "https://darkcrystal.pw") - A FLOSS “secret sharing” system based on the Scuttlebutt protocol. Private data, such as passwords, are broken into “shards” that are then stored on the computers of several trusted parties. All of the shards are encrypted and none can be used to work out even a portion of the secret without bringing all of them together, meaning your info is safe until you need it.
-   [Cryptpad](https://cryptpad.fr/ "https://cryptpad.fr/") CryptPad is a private-by-design alternative to popular office tools and cloud services.

—-

## Operating Systems

An operating system (OS) is system software that manages computer hardware and software resources and provides common services for computer programs.

-   [Debian](http://debian.org/ "http://debian.org/") - Unix-like operating system composed entirely of free software packaged by a team of volunteers. The Debian stable branch is the most popular edition for personal computers and network servers, and is used as a base for many other distributions. A popular user-friendly distribution is [Ubuntu](https://www.ubuntu.com/ "https://www.ubuntu.com/"); this has ads and leaks on by default, however they can be simply [turned off](https://www.eff.org/deeplinks/2012/10/privacy-ubuntu-1210-amazon-ads-and-data-leaks "https://www.eff.org/deeplinks/2012/10/privacy-ubuntu-1210-amazon-ads-and-data-leaks").
-   [Fedora](https://fedoraproject.org/ "https://fedoraproject.org/") - Linux distribution developed by the community-supported Fedora Project and sponsored by Red Hat. Fedora contains software distributed under various free and open-source licenses and aims to be on the leading edge of such technologies. Fedora has a reputation for focusing on innovation, integrating new technologies early on and working closely with upstream Linux communities. Making changes upstream instead of specifically for Fedora ensures that the changes are available to all Linux distributions. [Qubes](https://www.qubes-os.org/ "https://www.qubes-os.org/") is a Fedora distribution that provides strong security through isolation of programs.
-   [LineageOS](https://lineageos.org/ "https://lineageos.org/") - LineageOS is a FLOSS operating system for set-top boxes, smartphones and tablet computers, based on the Android mobile platform. It is the successor to the custom ROM CyanogenMod, from which it was forked in December 2016. It has a couple forks: one makes it compatible with [microG](https://lineage.microg.org/ "https://lineage.microg.org/"), eliminating reliance on Google services while preserving user-friendliness; the other is the very in-development [Replicant](https://replicant.us/ "https://replicant.us/"), which aims to eliminate all proprietary components.
-   [Tails](https://tails.boum.org/ "https://tails.boum.org/") - The Amnesic Incognito Live System (TAILS) is a security-focused Debian-based Linux distribution aimed at preserving privacy and anonymity. All its outgoing connections are forced to go through Tor, and non-anonymous connections are blocked. The system is designed to be booted as a live DVD or live USB, and will leave no digital footprint on the machine unless explicitly told to do so. [Last tails audit was back in 2011](https://tails.boum.org/security/audits/ "https://tails.boum.org/security/audits/")

___

## Social Networks

A distributed social network or federated social network is an Internet social networking service that is decentralized and distributed across distinct providers.

-   [Mastodon](https://joinmastodon.org/ "https://joinmastodon.org/") - A distributed, federated microblogging platform.
-   [Diaspora](https://diasporafoundation.org/ "https://diasporafoundation.org/") - A user-owned, distributed social network.
-   [Friendica](https://friendi.ca/ "https://friendi.ca/") - A FLOSS, distributed social network.
-   [Okuna](https://www.okuna.io/en/home "https://www.okuna.io/en/home") An ethical social network for a brighter tomorrow.
-   [Mahara](https://mahara.org/ "https://mahara.org/") Fully-featured open source web application to build your electronic portfolio. Learner-centered personal learning environment.

—-

## Web Search Engines

A web search engine is a software system that is designed to search for information on the World Wide Web. The search results are generally presented in a line of results. The information may be a mix of web pages, images and other types of files.

-   [DuckDuckGo](https://duckduckgo.com/ "https://duckduckgo.com/") - An Internet search engine, hosted around the world, that emphasizes protecting searchers' privacy and avoiding the filter bubble of personalized search results. It has some open-source component.
-   [Searx](http://searx.me/ "http://searx.me/") - A FLOSS metasearch engine with the aim of protecting the privacy of its users.
-   [Ecosia](https://ecosia.org/ "https://ecosia.org/") - A private web search engine based in Berlin, Germany, which donates 80% of its surplus income to non-profit conservationist organizations, with a focus on tree planting.

___

## Open Source Software

Open-source software is a type of computer software in which source code is released under a license in which the copyright holder grants users the rights to study, change, and distribute the software to anyone and for any purpose. Open-source software may be developed in a collaborative public manner.

-   [LibreOffice](https://www.libreoffice.org/ "https://www.libreoffice.org/") -LibreOffice is the leading open-source office software suite for word processing, spreadsheets, presentations, graphics, databases and more.
-   [Nextcloud](https://nextcloud.com/ "https://nextcloud.com/") -Share and collaborate on documents, send and receive email, manage your calendar and have video chats without data leaks. Nextcloud Hub provides the benefits of online collaboration without the compliance and security risks.
-   [ClamAV](https://www.clamav.net "https://www.clamav.net") -ClamAV® is an open source antivirus engine for detecting trojans, viruses, malware & other malicious threats.
-   [Linshare](https://www.linshare.org/en/index.html "https://www.linshare.org/en/index.html") -Linshare is an Open Source secure file sharing application intended to cover your business security and file transfer needs. If confidentiality and traceability are paramount for your business file transfers, then LinShare is your solution and better yet it's free !
-   [OnionShare](https://onionshare.org/ "https://onionshare.org/") -OnionShare is an open source tool that lets you securely and anonymously share a file of any size.
-   [Thunderbird](https://www.thunderbird.net/en-GB/ "https://www.thunderbird.net/en-GB/") -Thunderbird makes email better for you, bringing together speed, privacy and the latest technologies.
-   [Keepass](https://keepass.info/ "https://keepass.info/") -KeePass is a free open source password manager, which helps you to manage your passwords in a secure way. You can store all your passwords in one database, which is locked with a master key. So you only have to remember one single master key to unlock the whole database.
-   [Shotcut](https://shotcut.org/ "https://shotcut.org/") -Shotcut is a free, open source, cross-platform video editor.
-   [VLC media player](https://www.videolan.org/vlc/index.html "https://www.videolan.org/vlc/index.html") -VLC is a free and open source cross-platform multimedia player and framework that plays most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols.
-   [7-zip](https://www.7-zip.org/ "https://www.7-zip.org/") -7-Zip is a file archiver with a high compression ratio. 7-Zip is free software with open source. You can use 7-Zip on any computer, including a computer in a commercial organization.
-   [qBittorrent](https://www.qbittorrent.org/ "https://www.qbittorrent.org/") -The qBittorrent project aims to provide an open-source software alternative to µTorrent. Additionally, qBittorrent runs and provides the same features on all major platforms (FreeBSD, Linux, macOS, OS/2, Windows).
-   [Jitsi](https://jitsi.org/ "https://jitsi.org/") Jitsi is a set of open-source projects that allows you to easily build and deploy secure videoconferencing solutions. At the heart of Jitsi are Jitsi Videobridge and Jitsi Meet, which let you have conferences on the internet, while other projects in the community enable other features such as audio, dial-in, recording, and simulcasting.
-   [Wire](https://wire.com/en/ "https://wire.com/en/") Wire offers the most comprehensive collaboration suite featuring messenger, voice, video, conference calls, file-sharing, and external collaboration – all protected by the most secure end-to-end-encryption.

#### Find out more open source software

-   [PRISM break](https://prism-break.org/en/ "https://prism-break.org/en/") Opt out of global data surveillance programs like [PRISM](https://en.wikipedia.org/wiki/PRISM_%28surveillance_program%29 "https://en.wikipedia.org/wiki/PRISM_%28surveillance_program%29"), [XKeyscore](https://en.wikipedia.org/wiki/XKeyscore "https://en.wikipedia.org/wiki/XKeyscore") and [Tempora](https://en.wikipedia.org/wiki/Tempora "https://en.wikipedia.org/wiki/Tempora")
-   [Awesome-Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted "https://github.com/awesome-selfhosted/awesome-selfhosted")This is a list of Free Software network services and web applications which can be hosted locally
-   [Open-source alternatives](https://opensource.builders/ "https://opensource.builders/")Find open-source alternatives for your favorite apps.

___

## Web Browsers

A web browser is a software application for accessing information on the World Wide Web. Each individual web page, image, and video is identified by a distinct URL, enabling browsers to retrieve and display them on the user's device.

-   [Firefox](https://mozilla.org/firefox "https://mozilla.org/firefox") - A FLOSS web browser developed by the Mozilla Foundation. You can safeguard your browsing habits and stop advertising companies from tracking you by installing addons including: Cookie AutoDelete, Decentraleyes, HTTPS Everywhere, NoScript, Privacy Badger and uBlock Origin.

Do not use brave. [Brave is sh\*\*](https://ebin.city/~werwolf/posts/brave-is-shit/ "https://ebin.city/~werwolf/posts/brave-is-shit/")

___

## Radio

-   [https://commonradio.org/](https://commonradio.org/ "https://commonradio.org/")

### How-Tos

-   [Riding the Airwaves](https://wiki.sunbeam.city/lib/exe/fetch.php?media=frequency_guide.pdf "frequency_guide.pdf (472.1 KB)") - A very quick and messy guide to how radio licensing in the US works and what you should purchase and work toward based on your communication needs. A pretty barebones work in progress right now.

___

## Hardware

-   [Hardware](https://wiki.sunbeam.city/doku.php?id=technology:hardware "technology:hardware")
-   A book on basic electronics
-   [Lantern Works](https://www.lantern.works "https://www.lantern.works") - a portable wireless device for stronger, safer recovery
-   [Heads: the other side of TAILS](https://github.com/osresearch/heads "https://github.com/osresearch/heads") - Heads is a configuration for laptops and servers that tries to bring more security to commodity hardware.
