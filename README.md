# BroGraph

<p align="center">
  <img src="media/bro.png" width="auto" >
</p>

---

## Intro
During the lockdowns of 2020, the frequency of messages in my Discord spiked and with it, the use of "bro", particularly "bro..."

It caught on like a bug.

I wanted to know who was the perpetrator of these "bro"s.

Thus this notebook was born.

**This notebook generates a video of the usages of that word over time**

## Running

1. Download [DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter)
2. Export the `[channelName].json` file with the above program and place in root folder
3. In the root `pip install -r REQUIREMENTS.txt` (Makes use of Python Package bar_chart_race)
4. Have [ffmpeg](https://www.ffmpeg.org/)
5. Open notebook and fill in variables for the word to track and the `[channelName].json` generated from the exporter
6. Run all cells and a video `bro.mp4` should appear in root

## Media
Names anonymised in gif
<p align="center">
  <img src="media/graphscreenshot.png" width="auto" >
  <img src="media/graph.gif" width="auto" >
</p>
