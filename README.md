# subtitles

```
chown -R www-data *
chgrp -R www-data *
chmod 755 *
```

ffmpeg -i serendipity.mp4 -vcodec h264 output.mp4
```
<html>
<head>
</head>
<body>
<video width="1280" height="720" controls autoplay>
    <source src="footloose.mp4" type="video/mp4">
    <track default src="footloose_es.vtt" kind="captions" srclang="es" label="Spanish">
    <track src="footloose.vtt" kind="captions" srclang="en" label="English">
</video>
</body>
</html>
~                
```


ffmpeg -i footloose.mp4 -c:v libx264 -profile:v main -vf format=yuv420p -c:a aac -movflags +faststart foot.mp4

sudo chown -R www-data:www-data /var/www

```
https://www.happyscribe.com/es/herramientas-de-subtitulacion/convertir-srt-a-vtt
https://www.syedgakbar.com/projects/dst
```

Convert mkv to mp4 using vlc
```
/Applications/VLC.app/Contents/MacOS/VLC --no-sout-all --audio-track=1 --no-repeat --no-loop -I dummy ./love.mkv --sout='#transcode{vcodec=h264,vb=1024,acodec=mp4a,ab=192,channels=2}:standard{access=file,mux=ts,dst=ouput.mp4}' vlc://quit
```


