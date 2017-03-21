# youtube-music

With `youtube-music`, it's never been easier to download full albums directly from YouTube. Downloaded music is converted to mp3 and automatically given the correct metadata (i.e. track number, artist name, and album name). Works on any UNIX-like system with the correct [dependencies](#Dependencies) installed.

# Dependencies

 * [curl](https://curl.haxx.se)
 * [id3v2](http://id3v2.sourceforge.net)
 * [youtube-dl](https://rg3.github.io/youtube-dl/)
   * [ffmpeg](https://ffmpeg.org) (for conversion to mp3)
 * [jq](https://stedolan.github.io/jq/)

# Usage

Simply copy `youtube-music` into your path (e.g. `/usr/local/bin`). Now, you can download music like so:

```
$ mkdir music_download
$ youtube-music "Green Day" music_download
Download "21st Century Breakdown (Deluxe Version)" by "Green Day"? [y/n]: y
Downloading...
Fetching Song of the Century.mp3 ...
Fetching 21st Century Breakdown.mp3 ...
Fetching Know Your Enemy.mp3 ...
...
```
