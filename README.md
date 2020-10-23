# Media

## Gource tutorial

How to generate a Gource video:

>  git log --pretty=format:"%at|%h - %an, %ai : %s" | sort -n > cp0.txt && awk '{print $s  " (#" NR  ")"}' cp0.txt > my_captions.txt && gource -s .05 -1920x1080 --auto-skip-seconds .1 --multi-sampling --stop-at-end --key --highlight-users --hide mouse,progress --file-idle-time 0 --max-files 0 --background-colour 000000 --font-size 22 --title "Linux Kernel"  --output-framerate 60 --caption-file my_captions.txt --caption-duration 1.5 --caption-offset -10 --output-ppm-stream - | ffmpeg -y -r 60 -vcodec ppm -f image2pipe -i - -c:v libx264 -crf 18 -preset slow -pix_fmt yuv420p -c:a copy gource.mp4
