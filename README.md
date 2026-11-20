# Daily Motivation ✨

A lightweight English and Persian motivational quote website. It pairs a responsive, animated interface with a personal saved-quotes library and settings that stay on the device.

## Features

- **Daily quote:** Start with one quote that stays consistent for the local calendar day, or choose a random opening quote in Settings.
- **Random inspiration:** Generate another quote whenever you like. The Spacebar shortcut can be enabled or disabled.
- **Saved quote library:** Save favorites, search your collection, sort it, open a saved quote, copy it, or remove it. You can also export the collection as a text file.
- **Copy and share:** Copy the currently displayed language selection or use the device's native share sheet when supported.
- **Personalized appearance:** Choose System, Light, or Dark theme and select Violet, Ocean, Rose, or Emerald accents.
- **Language display:** Show English only, Persian only, or both languages together.
- **Effects:** Turn particle effects on or off. The app also respects the operating system's reduced-motion preference.
- **Responsive design:** The quote experience, Saved library, and Settings panel adapt to desktop and mobile screens.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Use the top-right controls to switch the theme or open Settings.
4. Save a quote with the heart button and open **Saved** to search or revisit it.

No build step, framework, backend, or API key is required. Favorites and preferences are stored in the browser's `localStorage`, so they are not automatically synchronized across devices.

## Project structure

- `index.html` contains the application, styles, quote collection, and client-side behavior.
- `site.webmanifest` contains the installable web app metadata.
- The remaining image files are the app icons.

## License

See [LICENSE](LICENSE).
