# Daily Learning
# This is an `<h1>` heading, which is the largest

<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">

## This is an `<h2>` heading

###This is an `<h6>`heading, which is the smalleste.

## Review Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4

