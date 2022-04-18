```ffmpeg -i input.mp4 -filter:v transpose=2 \
-c:v libx264 -preset veryfast -crf 22 \
-c:a copy \
-metadata:s:v rotate="" \
output-rotated.mp4```

2 is for counterclockwise, 1 for clockwise rotation
