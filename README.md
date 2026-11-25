# CSS Gradient Composer

Build CSS linear, radial, and conic gradients with a live preview and one-click copy.

**Live demo:** https://0xelitesystem.github.io/css-gradient-composer/

## Use

1. Open the tool and pick a gradient type: linear, radial, or conic.
2. Set the angle (linear and conic), or the shape, size, and center position (radial and conic).
3. Add color stops, tweak each stop's color, position, and opacity, or remove stops down to a minimum of two.
4. Click a preset swatch for a quick starting point, or hit Randomize to explore.
5. Copy the generated `background:` declaration and paste it into your stylesheet.

The preview sits on a checkerboard so transparent stops are visible. Stops that use less than 100 percent opacity are emitted as `rgba()`, otherwise the plain hex value is used.

## Why this exists

Most online gradient builders load trackers, fonts, and third-party scripts, then ask you to sign up to save anything. This is one HTML file. No accounts, no surveillance, no network calls. You can read every line, host it yourself, or drop it in a folder and open it offline. It is MIT licensed, so fork it and change whatever you want.

## Privacy

Everything runs in your browser. Your colors, stops, and generated CSS never leave your machine. There is no analytics, no telemetry, and no server. Load the page once and it works with your network unplugged.

## Run locally

```
git clone https://github.com/0xelitesystem/css-gradient-composer.git
cd css-gradient-composer
```

Then open `index.html` directly in any browser, or serve it locally:

```
python -m http.server
```

and visit http://localhost:8000.

## Build

There is no build step. It is a single self-contained `index.html` with inline CSS and JavaScript and no dependencies. Edit the file, refresh the browser.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. See [LICENSE](LICENSE).

## Related

- https://github.com/0xelitesystem/jwt-inspector
- https://github.com/0xelitesystem/wcag-contrast-ratio-check
- https://github.com/0xelitesystem/layered-box-shadow-builder
