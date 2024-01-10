# yt-dlp-download-script
An extremely simple powershell script that simplifies downloading mp4 videos from youtube, made for my personal use.

Just copy the code in the `$PROFILE` file and paste it into your own `$PROFILE`.

#### Usage
````
ytdl https://www.youtube.com/watch?v=xvFZjo5PgG0
````

Assuming you installed yt-dlp via winget `winget yt-dlp`, the videos will be downloaded to your `Downloads` folder. Because the script uses the url as the filename it will definitely create new folders. So a video downloaded from the above URL would be located in the  `https#\www.youtube.com` folder.
