### FFMPEG
---
https://github.com/FFmpeg/FFmpeg

https://ffmpeg.org/ffmpeg.html

```
ffmpeg -i input.avi -b:v 64k -bufsize 64k output.avi
ffmpeg -i input.avi -r 24 output.avi
ffmpge -r 1 -i input.m2v -r 24 output.avi

ffmpeg -i A.avi -i B.mp4 out1.mkv out2.wav -map 1:a -c:a copy out3.mov

```

```
```

```
```
