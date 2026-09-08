# Focus Sprint

A minimalist [Pomodoro](https://en.wikipedia.org/wiki/Pomodoro_Technique) focus timer with lightweight task tracking. Single HTML file, no build step, no accounts — everything saves locally in your browser.

## Features

- **25 / 5 timer** with adjustable work and break lengths
- **Task list** — add tasks, tap one to focus your next sprint on it, check it off when done
- **Daily stats** — sprints completed, total focus time, and a row of "bricks" for the day
- **Keyboard shortcut** — press `Space` to start/pause
- **Local-only** — state is stored in `localStorage`; nothing leaves your machine
- Audio chime and vibration (on supported devices) when a sprint ends

## Usage

Open `index.html` in any modern browser. That's it.

To serve it locally instead:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Development

There's no toolchain — the app is plain HTML, CSS, and vanilla JavaScript in [`index.html`](index.html). Edit the file and refresh.

## License

MIT
