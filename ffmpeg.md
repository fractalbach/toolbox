# ffmpeg tricks


Scale down a video's width and height to help reduce filesize
```
ffmpeg -i file1.mp4 -vf "scale=trunc(iw/10)*2:trunc(ih/10)*2" file2.mp4
```
