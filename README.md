![banner](https://github.com/user-attachments/assets/059f29d1-ec41-463f-91eb-a7a333c1e107)
# YT-dlp Downloader for Windows (GUI, Kind of)
A lightweight GUI based on Windows VBS script that uses yt-dlp to download videos or playlists from YouTube and other supported platforms, with selectable resolution.

### Features
* Can download a single video or a playlist or a freakin whole channel.
* Selectable videos from playlist. (It lists Videos, Shorts, Lives but download only works for videos now, it's a YT-DLP issue btw)
* Video or Audio download.
* Multiple formats for both Videos and Audio.
* Selectable quality (Best, Worst, 144p, 240p, 360p, 480p, 720p, 1080p, 1440p, 2160p and 4320p).
* Supports cookies (place cookies.txt inside the same folder).
* Subtitles (Auto-generated and Manual both, selective)
* Description Download.
* Embedded Metadata.
* Update Check. (Selectable)
* Video overwrite protection.

### Requirements
* Functional Brain
* [yt-dlp](https://github.com/yt-dlp/yt-dlp)
* [ffmpeg](https://ffmpeg.org/download.html) for conversion ofcourse. (Checkout Notes)

### How to use:
* Simply put the vbs script into your yt-dlp folder and run from there, follow instructions.
* Files are downloaded to "Downloads" folder automatically created inside the folder.

### Screenshots:
![screenshots](https://github.com/user-attachments/assets/da3017ea-3260-44fe-af72-1de4b7b38b93)


### NOTE:
* You gotta use ffmpeg (download ffmpeg and put "ffmpeg/bin" folder path into your Enviromental Values Path) to get both video and audio merged. Else you'll get separate audio and video file.
* If the subtitles aren't found, it'll just download the video.
