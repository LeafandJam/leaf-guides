---
title: "Youtube-dlp"
date: 2022-05-30T15:46:37+09:30
draft: false
categories: ["YouTube"]
---
Youtube-dlp is an updated fork of Youtube-dl with many extra features. (Youtube-dl has become inactive)

This app allows you to download youtube videos to .mp3 and .mp4 easily and quickly.

The following guide was written by [Krimsen](https://www.reddit.com/user/krimsen/) on reddit. It is the easiest and most fool-proof way to install Youtube-dlp. This is a cleaned up copy however the original guide can be found [here](https://www.reddit.com/r/youtubedl/comments/qzqzaz/can_someone_please_post_a_simple_guide_on_making/hlon6k5/).

# How To Download & Install yt-dlp on Windows
1.    [Download yt-dlp for Windows](https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp.exe) ←← This link will point you directly to the latest yt-dlp.exe file.

2.    Create ```c:\ytdl``` and put the file you downloaded from above in that directory. Just put it there. There is no installation. The EXE that you downloaded is the program itself.

3.    [Download yt-dlp's custom ffmpeg build](https://github.com/yt-dlp/FFmpeg-Builds/wiki/Latest) ← Download the win64-gpl variant

4.    [Download 7Zip (a free, open source alternative to Winzip)](https://www.7-zip.org/download.html) - Specifically, under the (currently) topmost heading "Download 7-Zip 21.07 (2021-12-26):", download the 64-bit Windows x64 EXE file. Note that "Download 7-Zip 21.06 (2021-11-24):" will change as new versions come out. Just always download the latest one.

5.    Install 7Zip (double click the file you downloaded and follow the on-screen instructions)

6.    Once 7Zip is installed, you should be able to double click on the ffmpeg file you downloaded a few steps ago and it will open in 7Zip

7.    Use 7Zip to extract the EXE files to ```c:\ytdl```. The other files in the ZIP are not needed.

8.    Close out of 7Zip

9.    Click your ```START``` button > type ```envir``` > Click Edit the system environment variables

10.    Click ```ENVIRONMENT VARIABLES``` (button at bottom right)

11.    Double click ```PATH``` in the top white section

12.    In the window that opens up, add this line:
        ```c:\ytdl```

14.    Click ```OK, OK, OK``` (close all 3 windows)

15.    yt-dlp is now installed. Below are commands for accomplishing some common tasks in yt-dlp.

# Run yt-dlp from the Command Line

1.    Click START> type CMD > Click on Command Prompt. __DO NOT__ open as Admin 

2.    Type ```cd \ytdl```

3.    Now that you are at the command line, you are ready to download.

4.    Go find a video you want to download. 

# Examples
## Download YouTube video as MP3

```yt-dlp -x --audio-format mp3 "https://www.youtube.com/watch?v=dQw4w9WgXcQ"```

## Download YouTube Video (audio + video)

```yt-dlp "https://www.youtube.com/watch?v=dQw4w9WgXcQ"```

