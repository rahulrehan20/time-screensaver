# Time Screensaver

A minimal fullscreen clock screensaver built as a single HTML file. It shows the current time in large, high-contrast type with the date in the corner, and includes simple controls for dark mode, light mode, and fullscreen display.

## Features

- Large digital clock with seconds
- Date display in `Weekday, YYYY-MM-DD` format
- Black and white display modes
- Fullscreen mode from the button or the `F` key
- Responsive layout for desktop and mobile screens
- No build step, dependencies, or external assets

## Getting Started

Clone the repository and open the HTML file in a browser:

```bash
git clone git@github.com:rahulrehan20/time-screensaver.git
cd time-screensaver
```

Then open `time-screensaver.html` directly in your browser.

You can also serve it locally if you prefer:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/time-screensaver.html
```

## Usage

- Click `Fullscreen` to enter fullscreen mode.
- Press `F` to enter fullscreen mode from the keyboard.
- Press `Esc` to exit fullscreen mode.
- Use `Black` or `White` to switch the display theme.

Browser fullscreen APIs require a user gesture, so fullscreen mode must be triggered by a click or key press.

## Customization

All code lives in [time-screensaver.html](time-screensaver.html). Common changes:

- Update the colors in the `:root` and `body.light` CSS variables.
- Change the clock size by editing the `.time` `font-size` clamp values.
- Adjust the date position in the `.date` rule.
- Change the date format in the `updateClock()` function.

## Project Structure

```text
.
├── README.md
└── time-screensaver.html
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
