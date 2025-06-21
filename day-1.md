# 🌤 Daily Learning

<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="200" align="right">

## Morning Planning

- [ ] Check out the [GitHub Blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review

Convert an image or video from dark mode to light mode using [FFmpeg](https://www.ffmpeg.org):

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
