# Fabled Theme For Replugged

<img src="./assets/image.png">

## Install

1. Clone this repository and cd into it
2. Install dependencies: `pnpm i`
3. Build the theme: `pnpm run build`
4. Reload Discord to load the theme

Or

1. Download
[this file](https://github.com/Teltta/fabled-theme/releases/latest/download/fabled-theme.zip)
.
2. Extract it into your themes folder.

Windows: `%APPDATA%\replugged\themes`
Linux: `~/.config/replugged/themes`

## Troubleshooting

### Make sure Replugged is installed and running.

Open Discord settings and make sure the Replugged tab is there. If not,
[follow these instructions](https://github.com/replugged-org/replugged#installation) to install
Replugged.

### Make sure the theme is installed.

Check the [theme folder](https://github.com/replugged-org/replugged#installing-plugins-and-themes)
for your OS and make sure the theme is there. If not, make sure you have built the theme and that
the `NO_INSTALL` environment variable is not set.  
You can run `replugged.themes.list().then(console.log)` in the console to see a list of themes in
the theme folder.
