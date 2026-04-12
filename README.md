![banner](https://github.com/user-attachments/assets/059f29d1-ec41-463f-91eb-a7a333c1e107)
# YT-dlp Downloader for Windows (GUI, Kind of)
A lightweight GUI based on Windows VBS script that uses yt-dlp to download videos or playlists from YouTube and other supported platforms, with selectable resolution.

### Features
* Can download a single video or an entire playlist.
* Selectable videos from playlist.
* Video or Audio download.
* Selectable WEBM (default, fast) , MP3 (Converted, bit slow) options for audio.
* Selectable quality (Best, Worst, 144p, 240p, 360p, 480p, 720p, 1080p, 1440p and 2160p)
* Supports cookies (place cookies.txt inside the same folder)
* Subtitles (Auto-generated and Manual both, selective as well)

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
