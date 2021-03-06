# Markdown-CLI
![GitHub issues](https://img.shields.io/github/issues/margual56/Markdown-CLI?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/margual56/Markdown-CLI?style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/margual56?style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/margual56/Markdown-CLI?style=for-the-badge)

A markdown CLI renderer in C++ <br/>

(Still in development)

## Goal
Simple syntax, concise commands and versatile while _trying_ to be suckless.

Command | Description
--- | ---
`markdown -i input.md output.html` | Reads the markdown from the file and outputs to another file.
`markdown output.html`             | Reads the markdown from the stdin (optional).
`markdown -i input.md`             | Reads the markdown from the file and writes the output to the stdout.
`markdown -i input.md -s style.css output.html` |  Reads the markdown from the file and outputs to another file, applying the styling rules specified in the css (includes a `<style></style>` tag in the html head).
`markdown -h` or `markdown --help` | Display the help (manual)

## Manual
The goal is to have here a wiki, implement the manual page and add it to the [tldr pages](https://github.com/tldr-pages/tldr).
