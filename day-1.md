# Daily Learning

## Morning Planning
<img src="https://octodex.github.com/images/cloud.jpg" alt="Cloudy morning" width="100" align="right"></img>
- [ ] Check out the [github blog](https://github.blog/) for ideas
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github)
- [ ] Convert my first blg post into an actual webpage

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)
``` bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
