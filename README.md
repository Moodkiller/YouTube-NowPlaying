### Setup 
1. Copy / download `youtube_nowplaying.py` to your Hexchat addons directory: `%appdata%\HexChat\addons`
2. In Hexchat, load the script with `/LOAD youtube_nowplaying.py`

### Usage
1. Play a song from YouTube in Chrome / Brave or Edge. The Script will look for "chrome" but seen as all three of these are based off it, it should work.
2. Type `/ytnp` into your desired channel
3. Output:   
<img width="914" alt="image" src="https://github.com/Moodkiller/YouTube-NowPlaying/assets/11341653/131d8864-2ad0-4c71-be54-d3142d929ee8">   

Note: the two lines above can be disabled, they are just part of the debugging.

### Features
* Uses API to scrape any info you like from a video. Currently setup to show Title, Channel, Views (human format), Likes (human format) and Uploaded timeframe (human format)
* Will display the current active playing song (i.e you can have mulitple YouTube tabs open but the script will only use the active tab as its source)
* If API reaches its limit / fails, script will fall back to just showing the title pulled from the active tab in the browser