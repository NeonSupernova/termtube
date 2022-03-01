# BUILDING

Building requires python3.10, and the build package, which can be installed via pip:
```bash
python3.10 -m pip install build
```

To install, run 
```bash
python3.10 -m pip install -r requirements.txt
python3.10 -m pip install dist/yt_feed-*.whl 
```


Now, add a channel via 
```bash
feed --add <channel-id>
```
where channel-id is for instance :
UCX6OQ3DkcsbYNE6H8uQQuVA of https://www.youtube.com/channel/UCX6OQ3DkcsbYNE6H8uQQuVA

# termtube
Search and Watch Youtube videos from terminal
# Requirements
- [fzf](https://github.com/junegunn/fzf)
- [rofi](https://github.com/davatorium/rofi) (optional)
- [mpv](https://mpv.io/installation/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) (Improved youtube-dl used here just to play video in mpv)
- [python3.x](https://www.python.org/downloads/)

# Screenshot :
![Get results from fzf](https://raw.githubusercontent.com/yeddaif/termtube/main/screenshots/termtube-fzf.png)

# Usage
## From you terminal :

Simply run :
```bash
    python3 main.y [option][search_query]
```
# Todo
- [ ] Get videos from channel or playlist
- [x] Optimization
- [x] Script to play videos