# osu! Replay Generation

This directory stores the method and settings I use to generate videos replays in the game, osu!.
I use the Danser project, https://github.com/Wieku/danser-go, which is significantly better than the osu2mp4 project due to it having continued development.
Danser generates the video file and FFMPEG is used to encode the video for compression

## TODO:
- [ ] Compare cursor size of replay to game
- [ ] Create video encoding settings (VP9 2-Pass Best/Good deadline)
- [ ] Find proper 960fps Motion Blur settings for Danser
- [ ] Modify skin to add cursor trails (Makes 960fps replays looks better)

## NOTE:
Settings file is generated from the project and only minorly edited to account for my game installation path and skin settings
