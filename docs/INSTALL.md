# Installation and usage instructions


Example:

```bash
theme_clipper --movies-directory /path/to/movies --clip-length 15
```

To clean up all Backdrops:

```bash
theme_clipper --shows-directory /path/to/shows --delete
```

### support config file

example config.json:

```json
{
  "movies_directory": "./data/movies/",
  "shows_directory": "./data/shows/",
  "clip_length": 10,
  "method": "random"
}
```

using config:

```bash
theme_clipper --config /path/to/config.json
```