Read me doc 2

convert to video using ffmpeg

date && ffmpeg -stats -loop 1 -i jj2.jpg -i uploads/phani-1675540907923.mp3 -vf "scale=1920:1080:force_original_aspect_ratio=decrease,pad=1920:1080:-1:-1:color=black,setsar=1,format=yuv420p" -speed 16 -preset ultrafast -shortest -fflags +shortest "yt-upload/out.mp4" && date

