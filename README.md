# ASCIIart

A looping ASCII-character animation with background music, built as a single web page.

## Run it

Open `index.html` in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

Click **Start animation & music** to begin. Browsers block sound until the visitor interacts with the page, so the animation waits for that click.

## Controls

- **Play / Pause** stops and resumes both the animation and the music.
- **Speed slider** changes how fast the frames advance (further right is faster).

## Files

- `index.html`: the page, styles and animation script
- `ASCII art anima.mp3`: the looping soundtrack

Made for [MLearning.ai](https://mlearning.substack.com).
