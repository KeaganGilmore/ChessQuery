# Chessboard – URL FEN

A simple, responsive chessboard that renders any FEN position from the URL.
Supports board orientation, themes, highlights, and coordinate labels.

## Usage

1. Open `index.html` in your browser.
2. Add FEN and options as URL parameters, e.g.:

'index.html?fen=rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR&theme=blue&orientation=black'

### URL Parameters

- `fen`: FEN string or `start` for the initial position
- `size`: Board size in pixels (default: 480)
- `theme`: `classic`, `blue`, `green`, `gray`
- `orientation` or `flip`: `white` or `black`
- `coords`: Show coordinates (`1`/`0`)
- `hl`: Comma-separated squares to highlight (e.g. `e4,d5`)
- `lastmove`: Last move (e.g. `e2e4`)

## Donate

If you find this project useful, consider donating:
**PayPal:** [keagangilmore@gmail.com](mailto:keagangilmore@gmail.com)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

The GPL-3.0 is a copyleft license that requires anyone who distributes this code or derivative works to make the source available under the same terms. This license ensures users have freedom to run, study, share, and modify the software.

Copyright (C) 2023 Keagan Gilmore
