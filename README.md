# NitroDJ

NitroDJ is a democratic radio station, allowing people to queue up songs to be played.

NitroDJ takes songs from YouTube and streams them to an Icecast Server.

## Installation

```shell script
sudo apt install libshout3 libshout3-dev ffmpeg
python3 -m pip install -r requirements.txt
export NITRO_ICECAST_HOST="example.com"
export NITRO_ICECAST_PORT="8000"
export NITRO_ICECAST_PASSWORD="password"
python3 index.py
```