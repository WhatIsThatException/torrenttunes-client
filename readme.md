[TorrentTunes](http://torrenttunes.tk) &mdash; A free, BitTorrent-based music streaming service.
==========
![](http://img.shields.io/version/0.1.0.png?color=green)


[TorrentTunes](http://torrenttunes.tk) is an open-source, [BitTorrent-based](https://en.wikipedia.org/wiki/BitTorrent) music service, like Rdio or Spotify, where you can stream any music, or share your own library of music with others.

Each individual song is tagged using [MusicBrainz](http://musicbrainz.org/), and shared as a *.torrent* file using the client's built-in, [LibTorrent-based](http://www.libtorrent.org/) BitTorrent client, on publicly available trackers.

TorrentTunes works on Windows, Mac OS X, and Linux.

Suggest features or post bugs [here](https://github.com/tchoulihan/torrenttunes-client/issues/), or on the subreddit [r/torrenttunes](http://www.reddit.com/r/torrenttunes).

[:arrow_down: Install TorrentTunes](https://github.com/tchoulihan/torrenttunes-client/releases/download/0.1.0/torrenttunes-client.jar)

## Features include
* A complete music streaming application including Artist and album pages, playlists, and settings.
* Fully categorized songs based on IDv3 tags and song duration with [MusicBrainz](http://musicbrainz.org/), with the [Musicbrainz-tagger](https://github.com/tchoulihan/musicbrainz-tagger).
* A [LibTorrent-based](http://www.libtorrent.org/) BitTorrent client.



## Screenshots:
<img src="http://i.imgur.com/vSA20Q5.png">
<img src="http://i.imgur.com/VGrtFSg.png">
<img src="http://i.imgur.com/j3OmWe8.png">



## Installation
### Requirements
- Java 8
- If behind a router, make sure bittorrent has enough open ports forwarded to your local IP address.

Download and double click the jar, located [here](https://github.com/tchoulihan/torrenttunes-client/releases/download/0.1.0/torrenttunes-client.jar)

Torrenttunes will install, create system shortcuts for Windows, Mac, or Debian-based Linux distributions, and load up in a browser window.

## Building from scratch

To build TorrentTunes, run the following commands:
```
git clone https://github.com/tchoulihan/torrenttunes-client
cd torrenttunes-client
chmod +x install.sh

# This script does a maven install, and java -jar command
./install.sh
```

## Support 
If you'd like to help fund me to keep developing [TorrentTunes](http://torrenttunes.tk), you can donate directly here:

[bitcoin:17N2wDi8Y6Cnrnrbzq5JsRcdjnW9DVyVhL](bitcoin:17N2wDi8Y6Cnrnrbzq5JsRcdjnW9DVyVhL)

![bitcoin:17N2wDi8Y6Cnrnrbzq5JsRcdjnW9DVyVhL](http://i.imgur.com/87N3QWu.png)

## Bugs and feature requests
Have a bug or a feature request? If your issue isn't [already listed](https://github.com/tchoulihan/torrenttunes-client/issues/), then open a [new issue here](https://github.com/tchoulihan/torrenttunes-client/issues/new).

## Contributing
Start with getting familiar with the [schema](http://ondras.zarovi.cz/sql/demo/?keyword=torrenttunes-client) first, then create some issues and we can start working on them. 

## Feature requests / todos
* TODO
