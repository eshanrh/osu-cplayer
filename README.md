# osu-cplayer
command line osu! song player built on mpv

## Dependencies
+ Python 3.4+
+ [mpv](https://mpv.io/installation/)
+ [python-mpv](https://github.com/jaseg/python-mpv)
+ [urwid](https://github.com/urwid/urwid/wiki/Installation-instructions)
+ [tinytag](https://github.com/devsnd/tinytag)

## Usage
1. Download `playmusic.py`
2. Edit `ABSPATH_TO_SONGS` to the absolute path of your osu! songs folder
3. Run with `python3 playmusic.py`

## Controls
+ Previous/Next Song: `left`/`right`
+ Move Selection: `up`/`down` or mouse movement
+ Play song: `enter`
+ Toggle play/pause: `p`
+ Quit: `q` or `esc`
+ Add song to queue: `a`