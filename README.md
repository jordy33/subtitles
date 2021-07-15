# subtitles

```
chown -R www-data *
chgrp -R www-data *
chmod 755 *
```

ffmpeg -i serendipity.mp4 -vcodec h264 output.mp4
```
<!DOCTYPE html>
<html>
<head>
</head>
<body>
<video width="1280" height="720" controls autoplay>
    <source src="somefile.mp4" type="video/mp4">
    <track default src="somefile.vtt" kind="captions" srclang="de" label="Deutsch">
</video>
</body>
</html>
```



ffmpeg -i 1080p.mp4 -c:v libx264 -profile:v main -vf format=yuv420p -c:a aac -movflags +faststart dianajorge.mp4


sudo chown -R www-data:www-data /var/www

```
https://www.happyscribe.com/es/herramientas-de-subtitulacion/convertir-srt-a-vtt
https://www.syedgakbar.com/projects/dst
```
