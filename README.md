<h1 align="center">ThemeClipper</h1>

<h4 align="center">Generate backdrops from movies and TV shows for Jellyfin. Built on <a href="https://rust-lang.org" target="_blank">Rust</a>.

ThemeClipper is a lightweight backdrop generator written in [Rust](https://rust-lang.org) that automatically creates live backdrops for your movies and TV shows using FFmpeg.
It follows Jellyfin's backdrop file structure, making integration seamless.

---

## Features

- Generates backdrops for movies and TV shows
- **Random method** for selecting clips
- Option to **delete all Backdrops folders**
- Compatible with Windows, macOS and Linux

---

## Roadmap

- [] **Audio-based** clip detection
- [] **Visual-based** scene analysis
- [] **Music-driven** theme clips

---

## Demo

![Demo](docs/assets/demo.gif)

👉 [Watch Full Demo Video](docs/assets/demo.mp4)

---

## Installation

> [!NOTE]
> For full installation and usage instructions, use [this]() file.

> [!IMPORTANT]
> Your system must have [FFmpeg](https://ffmpeg.org/) installed and added to its PATH environment variable.

1. Download the latest release for your platform from the [Releases](https://github.com/kumarvivek1752/ThemeClipper/releases) page.

2. Run the downloaded file to get started.

---

## Usage

```bash
theme_clipper [OPTIONS]

      --movies-directory <MOVIES_DIRECTORY>
          Path to movies directory
      --shows-directory <SHOWS_DIRECTORY>
          Path to shows/series directory
  -c, --clip-length <CLIP_LENGTH>
          Clip length in seconds (default: 10)
  -m, --method <METHOD>
          Method: random | audio | visual | music (default: random)
          Note: currently only "random" is supported
      --delete
          Delete all Backdrops folders from the given directory
      --config <CONFIG>
          Path to config JSON file
  -h, --help
          Show help message
  -V, --version
          Show version
```

---

## ❤️ Support & Contributions

- 💡 Created with love by **Vivek ([@kumarvivek1752](https://github.com/kumarvivek1752))**
- 💝 Donate via [PayPal](https://paypal.me/kumarvivek1752)
- 🙏 If you find ThemeClipper useful, consider **supporting or starring ⭐ the repo** to keep the project alive!