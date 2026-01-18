README.md在“player”文件夹
README.md is in “player” folder
if you need the command to make video into frames, there's an example（need ffmpeg）:
如果你需要制作视频到帧的命令，这有一个示例（需要安装ffmpeg）
ffmpeg -i 1.mp4 -vf scale=320:240 -r 10 -q:v 5 %04d.jpg
