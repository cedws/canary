# Canary
A simple and clean theme for Hugo. Currently work-in-progress.

## Features
- Built for a mobile-first experience
- Support for Chroma syntax highlighting
- No reliance on external CDNs
- No JavaScript

## Example `config.toml`

```
theme = "canary"
title = "Interesting Blog"
pygmentsStyle = "monokai"
pygmentsCodeFences = true
enableRobotsTXT = true

[params.seo]
  description = "A blog about interesting things."
  index = true

[params.links]
[params.links.github]
  href = "https://github.com"
  username = "john-smith"

[permalinks]
blog = "/post/:title/"
```