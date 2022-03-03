# Canary
A simple and clean theme for Hugo.

## Features
- Built for a mobile-first experience
- Support for Chroma syntax highlighting
- No reliance on external CDNs
- No JavaScript

## Example `config.toml`

```
theme = "canary"
title = "Interesting Blog"
enableRobotsTXT = true

[params]
lang = "en-GB"

[params.seo]
description = "A blog about interesting things."
tagline = "Blogs are useful!"
index = true

[params.links]
[params.links.github]
href = "https://github.com/john-smith"

[permalinks]
blog = "/post/:title/"
```