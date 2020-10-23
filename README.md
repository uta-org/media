# Media

## Gource tutorial

How to generate a Gource video:

>  git log --pretty=format:"%at|%h - %an, %ai : %s" | sort -n > cp0.txt && awk '{print $s  " (#" NR  ")"}' cp0.txt > my_captions.txt && gource -s .05 -1920x1080 --auto-skip-seconds .1 --multi-sampling --stop-at-end --key --highlight-users --hide mouse,progress --file-idle-time 0 --max-files 0 --background-colour 000000 --font-size 22 --title "Linux Kernel"  --output-framerate 60 --caption-file my_captions.txt --caption-duration 1.5 --caption-offset -10 --output-ppm-stream - | ffmpeg -y -r 60 -vcodec ppm -f image2pipe -i - -c:v libx264 -crf 18 -preset slow -pix_fmt yuv420p -c:a copy gource.mp4

### Generated Gource videos

#### z3nth10n Bot

[![...](https://img.youtube.com/vi/MYctk2xauME/maxresdefault.jpg)](https://www.youtube.com/watch?v=MYctk2xauME&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=1)

#### z3nth10n.net

[![...](https://img.youtube.com/vi/G8ejECSUS9A/maxresdefault.jpg)](https://www.youtube.com/watch?v=G8ejECSUS9A&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=2)

#### vizzuta.net

[![...](https://img.youtube.com/vi/Ox-CBNlKxGw/maxresdefault.jpg)](https://www.youtube.com/watch?v=Ox-CBNlKxGw&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=3)

#### uzTerraMaps

[![...](https://img.youtube.com/vi/KsO44WeLVRE/maxresdefault.jpg)](https://www.youtube.com/watch?v=KsO44WeLVRE&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=4)

#### uzSurfaceMapper

[![...](https://img.youtube.com/vi/11kd4bNr2Pw/maxresdefault.jpg)](https://www.youtube.com/watch?v=11kd4bNr2Pw&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=6)

#### uzSurfaceMapperDemo

[![...](https://img.youtube.com/vi/723FV06SG8Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=723FV06SG8Q&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=5)

#### uzCraft

[![...](https://img.youtube.com/vi/NwWzFwNP9k4/maxresdefault.jpg)](https://www.youtube.com/watch?v=NwWzFwNP9k4&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=7)

#### Unity Theft Auto

[![...](https://img.youtube.com/vi/Wze_2qUvqG4/maxresdefault.jpg)](https://www.youtube.com/watch?v=Wze_2qUvqG4&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=8)

#### T121 Project

[![...](https://img.youtube.com/vi/e0tslz3O8J4/maxresdefault.jpg)](https://www.youtube.com/watch?v=e0tslz3O8J4&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=9)

#### SteamScraper

[![...](https://img.youtube.com/vi/e2sRm0Qy8g4/maxresdefault.jpg)](https://www.youtube.com/watch?v=e2sRm0Qy8g4&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=10)

#### Steam Crawler

[![...](https://img.youtube.com/vi/xNObcf2FR6I/maxresdefault.jpg)](https://www.youtube.com/watch?v=xNObcf2FR6I&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=11)

#### SMF Bot

[![...](https://img.youtube.com/vi/btGsaYEpih8/maxresdefault.jpg)](https://www.youtube.com/watch?v=btGsaYEpih8&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=12)

#### servers.vizzuta.net

[![...](https://img.youtube.com/vi/wr4XEagpJH8/maxresdefault.jpg)](https://www.youtube.com/watch?v=wr4XEagpJH8&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=13)

#### San Andreas Unity

[![...](https://img.youtube.com/vi/APxJbHbROsg/maxresdefault.jpg)](https://www.youtube.com/watch?v=APxJbHbROsg&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=14)

#### QuickFork

[![...](https://img.youtube.com/vi/TVBJAs04czk/maxresdefault.jpg)](https://www.youtube.com/watch?v=TVBJAs04czk&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=15)

#### ProductoEspaña.es

[![...](https://img.youtube.com/vi/betAUeojfno/maxresdefault.jpg)](https://www.youtube.com/watch?v=betAUeojfno&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=16)

#### Lerp2API

[![...](https://img.youtube.com/vi/sttrRPA0wbc/maxresdefault.jpg)](https://www.youtube.com/watch?v=sttrRPA0wbc&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=17)

#### Free Rider 2 Port

[![...](https://img.youtube.com/vi/4AmL01oNDc8/maxresdefault.jpg)](https://www.youtube.com/watch?v=4AmL01oNDc8&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=18)

#### uzLib.Lite

[![...](https://img.youtube.com/vi/VXEyy9fOnBc/maxresdefault.jpg)](https://www.youtube.com/watch?v=VXEyy9fOnBc&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=19)

#### DepotToolkit

[![...](https://img.youtube.com/vi/T-XZ8Xt7lrA/maxresdefault.jpg)](https://www.youtube.com/watch?v=T-XZ8Xt7lrA&list=PLm_JmdfuMZ5BPTYTF_x1tK9pkt-UCxI7j&index=20)
