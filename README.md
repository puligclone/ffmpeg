# ffmpeg
You need to prepend a `!` to execute a shell command in Goole Colab or Jupyter

```
!git clone https://github.com/puligclone/ffmpeg.git
!cp -r ./FFmpegColab/bin/. /usr/bin/
!chmod +x /usr/bin/ffmpeg
!chmod +x /usr/bin/SvtAv1EncApp
!chmod +x /usr/bin/aomenc
!chmod +x /usr/bin/x265
```

Check the installed ffmpeg version
```!ffmpeg -version```

#Congratulations, ffmpeg with cuda support is installed!
