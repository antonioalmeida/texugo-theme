# Texugo 🦡

Minimalistic website theme for Hugo based on the [Tex](https://en.wikipedia.org/wiki/TeX)'s typography. 
 
![](./images/screenshot.png)

## Getting Started

Clone this repository to your hugo theme directory.

```
mkdir themes
cd themes
git clone https://github.com/antonioalmeida/tex-hugo-theme.git
```

## Configuration

Take a look in the [exampleSite](https://github.com/antonioalmeida/antonioalmeida.github.io) repository.

This directory contains an example config file and the content for the demo.
It serves as an example setup for your documentation.

Copy the `config.toml` in the root directory of your website. Overwrite the existing config file if necessary.

__[config.toml](https://github.com/antonioalmeida/tex-hugo-theme/blob/master/exampleSite/config.toml)__:

```toml
baseurl = "https://example.com"
languageCode = "en"
title = "Texugo"
theme = "tex-hugo-theme"
copyright = "&copy; <a href=\"https://github.com/antonioalmeida\">António Almeida</a> 2020"
disqusShortname = ""
googleAnalytics = ""

[params]

[params.highlight]
  style = "zenburn"

[[params.social]]
  url = "about.html"
  fa_icon = "fas fa-info" 

[[params.social]]
  url = "https://github.com/natarajmb"
  fa_icon = "fab fa-github"

[[params.social]]
  url = "https://www.linkedin.com/in/natarajmb/"
  fa_icon = "fab fa-linkedin-in"

[[params.social]]
  url = "https://twitter.com/natarajmb"
  fa_icon = "fab fa-twitter"
```

## Development

```shell
$ hugo server
```

You can go to localhost:1313 and this theme should be visible.

## Inspired by
- [Tex](https://en.wikipedia.org/wiki/TeX)
- [WiTex](https://github.com/AndrewBelt/WiTeX)

## How to tweak
- Once you have activited the theme as above and running hugo in server mode
- Install [npm](https://www.npmjs.com/get-npm)
- Get inside checked-out theme directory and run `npm install`
- Make required changes to style.scss and run `npm run css-build && npm run css-watch` to live update your changes

## License

`tex-hugo-theme` is licensed under the [MIT License](LICENSE.md).

## Author

[António Almeida](https://github.com/antonioalmeida)
