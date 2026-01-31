# JellyPitchPixel

A custom CSS theme for Jellyfin with a minimalist dark aesthetic and pixel-style fonts.
Still work in progress!

<img src=".github/images/screenshot.png" alt="JellyPitchPixel Screenshot" width="600">

## Features

- **Pixel Font** - Silkscreen font for section titles and card text
- **Dark Theme** - Pure black background with white accents (no blue)
- **Clean UI** - Hidden redundant elements (Home/Favorites tabs, Cast/Sync buttons)
- **Square Buttons** - Consistent square design for all buttons
- **Round Profile Picture** - Profile image stays round while button is square
- **Custom Logo** - Replace default Jellyfin logo with your own
- **TV Compatible** - Optimized for LG webOS and other TV clients
- **White Progress Bars** - Clean white playback indicators
- **No Hover Effects** - Minimal hover states for a cleaner look

## Installation

Add this single line to your Jellyfin Custom CSS (Dashboard → General → Branding):

```css
@import url("https://cdn.jsdelivr.net/gh/Saulimedes/JellyPitchPixel@main/index.css");
```

> **Note:** We use jsDelivr CDN because raw GitHub URLs serve CSS with incorrect MIME types, which browsers block.

## Customization

To use your own logo, replace the base64-encoded image in the CSS under the `/* Custom Logo in header */` section.

## Compatibility

- Jellyfin Web
- Jellyfin for LG webOS
- Other Jellyfin clients that support custom CSS

## License

GPL-3.0 - See [LICENSE](LICENSE) for details.
