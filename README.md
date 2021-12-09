# yt-dlp-concat

Downloads a playlist with yt-dlp and concatenates the files using the concat demuxer.

**Only works if all files have the same codec and codec parameters!**

## Synopsis
```
yt-dlp-concat [OPTIONS] URL [-- yt-dlp-options]
```
## Options
```
-c, --container <CONTAINER>  Target container format (e.g. mp4, mkv).
-d, --dir <DIRECTORY>        Output directory. Default is the current working directory.
-h, --help                   Show this help message.
-o, --output <FILE>          Output file relative to <DIRECTORY>.
```
## Licence

MIT