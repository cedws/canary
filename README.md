# Canary
A simple and clean theme for Hugo. Currently work-in-progress.

## Features
- Built for a mobile-first experience
- Support for PWA
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

[params]
  author = "John Smith"
  avatar = "/img/avatar.png"

[params.links]
[params.links.github]
  href = "https://github.com"
  username = "john-smith"

[permalinks]
blog = "/post/:title/"

```